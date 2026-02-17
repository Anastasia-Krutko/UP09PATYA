<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Метрики производительности</title>
    <style>
        table {
            border-collapse: collapse;
            width: 100%;
            max-width: 400px;
            font-family: Arial, sans-serif;
        }
        th, td {
            border: 1px solid #ddd;
            padding: 12px;
            text-align: left;
        }
        th {
            background-color: #f2f2f2;
            font-weight: bold;
        }
        tr:nth-child(even) {
            background-color: #f9f9f9;
        }
        .metric { font-weight: bold; }
        .target { color: #2196F3; }
    </style>
</head>
<body>
    <h2>Метрики производительности</h2>
    <table>
        <thead>
            <tr>
                <th>Метрика</th>
                <th>До оптимизации</th>
                <th>Цель</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td class="metric">Performance Score</td>
                <td>82</td>
                <td class="target">&gt; 90</td>
            </tr>
            <tr>
                <td class="metric">FCP</td>
                <td>0.5s</td>
                <td class="target">&lt; 1.8s</td>
            </tr>
            <tr>
                <td class="metric">LCP</td>
                <td>3.4s</td>
                <td class="target">&lt; 2.5s</td>
            </tr>
            <tr>
                <td class="metric">CLS</td>
                <td>0</td>
                <td class="target">&lt; 0.1</td>
            </tr>
            <tr>
                <td class="metric">TBT</td>
                <td>0ms</td>
                <td class="target">&lt; 200ms</td>
            </tr>
        </tbody>
    </table>
</body>
</html>
