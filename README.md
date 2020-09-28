# dothome1

#test 01
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>화면설계  test</title>
    <style>
        /* font */
        @font-face {
            font-family: 'S-CoreDream-8Heavy';
            src: url('https://cdn.jsdelivr.net/gh/projectnoonnu/noonfonts_six@1.2/S-CoreDream-8Heavy.woff') format('woff');
            font-weight: normal;
            font-style: normal;
         }

        /* reset */
        *{ margin: 0; padding: 0;}

        /* layout */
        body{ background:#ffebee;}
        #wrap {
            width: 1200px; 
            height: 1600px;
            margin: 0 auto;
            font-size: 72px;
            text-align: center;
            color:#fff;
            text-transform: uppercase;
            font-family: 'S-CoreDream-8Heavy';
        }
        #header {
            width: 1200px; 
            height: 150px; 
            line-height:150px;
            background:#ffcdd2;
        }
        #nav {
            width: 1200px; 
            height: 150px;
            line-height:150px;
            background:#ef9a9a;
        }
        #side {
            width: 300px; 
            height: 1100px;
            line-height:1100px;
            background:#e57373;
            float: left;
        }
        #contents1 {
            width: 900px;
            height: 370px; 
            line-height:370px;
            background:#ef5350;
            float: left;
        }
        #contents2 {
            width: 900px;
            height: 360px; 
            line-height:360px;
            background:#f44336;
            float: left;
        }
        #contents3 {
            width: 900px;
            height: 370px; 
            line-height:370px;
            background:#e53935;
            float: left;
        }
        #footer {
            width: 1200px; 
            height: 200px;
            line-height:200px;
            background: #c62828;
            clear: both;
        }
    </style>
</head>
<body>
    <div id="wrap">
        <div id="header">header</div>
        <div id="nav">nav</div>
        <div id="side">side</div>
        <div id="contents1">contents1</div>
        <div id="contents2">contents2</div>
        <div id="contents3">contents3</div>
        <div id="footer">footer</div>
    </div>
    <!-- //wrap -->
</body>
</html>
