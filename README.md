<!DOCTYPE html>
<html>
<head>
    <style>
        /* CSS to make all list items bold */
        #myList li {
            font-weight: bold;
        }
    </style>
</head>
<body>
    <ul id="myList">
        <li>Item 1</li>
        <li>Item 2</li>
        <li>Item 3</li>
        <li>Item 4</li>
    </ul>
    <script>
        // JavaScript to add a green background to the third element
        var thirdListItem = document.getElementById('myList').getElementsByTagName('li')[2];
        thirdListItem.style.backgroundColor = 'green';
    </script>
</body>
</html>

