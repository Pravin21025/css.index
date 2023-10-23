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



<!DOCTYPE html>
<html>
<head>
    <style>
        .item {
            background-color: green; /* Set the background color for all items */
        }
    </style>
</head>
<body>
    <ul id="itemList">
        <li class="item">Item 1</li>
        <li class="item">Item 2</li>
        <li class="item">Item 3</li>
    </ul>

    <script>
        // Change the background color of the 2nd item
        var secondItem = document.querySelector('#itemList .item:nth-child(2)');
        secondItem.style.backgroundColor = 'green';

        // Make the 3rd item invisible
        var thirdItem = document.querySelector('#itemList .item:nth-child(3)');
        thirdItem.style.display = 'none'; // This will hide the element
    </script>
</body>
</html>

