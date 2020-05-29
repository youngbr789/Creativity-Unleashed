<!DOCTYPE html>
<html>
<head>
    <title>100-Numbers</title>
</head>
<body>
    <script>
        var points = new Array(100);
        var label = points.length;
        for (var i = 0; i < 100; i++) {
                                points[i] = i+1;
            console.log(points[i]);
        }
    </script>
</body>
</html>

        for (var i = 0; i < points.length; i++) {
            console.log(points[i]); //This prints the values that you stored in the array
        }
