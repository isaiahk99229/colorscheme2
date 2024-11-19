# colorscheme2<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Color Scheme Table</title>
    <style>
        /* General styles for the table */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 20px;
            background-color: #f4f4f4;
        }
        table {
            width: 80%;
            margin: auto;
            border-collapse: collapse;
            background-color: white;
        }
        th, td {
            padding: 12px;
            text-align: center;
            border: 1px solid #ddd;
        }
        th {
            background-color: #4CAF50;
            color: white;
        }
        td {
            background-color: #f9f9f9;
        }
        caption {
            font-size: 1.5em;
            margin-bottom: 10px;
            font-weight: bold;
        }

        /* Color Swatches */
        .color-swatch {
            height: 30px;
            width: 100%;
        }
    </style>
</head>
<body>

    <h1>Color Scheme Table</h1>

    <table>
        <caption>Color Schemes</caption>
        <thead>
            <tr>
                <th>Scheme Name</th>
                <th>Color Name</th>
                <th>HEX Value</th>
                <th>RGB Value</th>
                <th>HSL Value</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Primary</td>
                <td>Red</td>
                <td>#FF0000</td>
                <td>rgb(255, 0, 0)</td>
                <td>hsl(0, 100%, 50%)</td>
            </tr>
            <tr>
                <td>Primary</td>
                <td>Green</td>
                <td>#00FF00</td>
                <td>rgb(0, 255, 0)</td>
                <td>hsl(120, 100%, 50%)</td>
            </tr>
            <tr>
                <td>Primary</td>
                <td>Blue</td>
                <td>#0000FF</td>
                <td>rgb(0, 0, 255)</td>
                <td>hsl(240, 100%, 50%)</td>
            </tr>
            <tr>
                <td>Secondary</td>
                <td>Yellow</td>
                <td>#FFFF00</td>
                <td>rgb(255, 255, 0)</td>
                <td>hsl(60, 100%, 50%)</td>
            </tr>
            <tr>
                <td>Secondary</td>
                <td>Cyan</td>
                <td>#00FFFF</td>
                <td>rgb(0, 255, 255)</td>
                <td>hsl(180, 100%, 50%)</td>
            </tr>
            <tr>
                <td>Secondary</td>
                <td>Magenta</td>
                <td>#FF00FF</td>
                <td>rgb(255, 0, 255)</td>
                <td>hsl(300, 100%, 50%)</td>
            </tr>
            <tr>
                <td>Neutral</td>
                <td>Black</td>
                <td>#000000</td>
                <td>rgb(0, 0, 0)</td>
                <td>hsl(0, 0%, 0%)</td>
            </tr>
            <tr>
                <td>Neutral</td>
                <td>White</td>
                <td>#FFFFFF</td>
                <td>rgb(255, 255, 255)</td>
                <td>hsl(0, 0%, 100%)</td>
            </tr>
        </tbody>
    </table>

</body>
</html>
