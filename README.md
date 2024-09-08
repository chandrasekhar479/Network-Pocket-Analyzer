<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Network Packet Analyzer</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: violet;
            margin: 0;
            padding: 0;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        #packetTable {
            width: 100%;
            border-collapse: collapse;
            margin: 25px 0;
            font-size: 18px;
            text-align: left;
        }
        #packetTable th, #packetTable td {
            padding: 12px;
            border-bottom: 1px solid #ddd;
        }
        #packetTable th {
            background-color: #333;
            color: white;
        }
        .header {
            background: #333;
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }
    </style>
</head>
<body>
    <div class="header">
        <h1>Network Packet Analyzer</h1>
        <p>Display of captured packets</p>
    </div>
    <div class="container">
        <table id="packetTable">
            <thead>
                <tr>
                    <th>Timestamp</th>
                    <th>Source IP</th>
                    <th>Destination IP</th>
                    <th>Protocol</th>
                    <th>Payload</th>
                </tr>
            </thead>
            <tbody>
               
                <tr>
                    <td>12:30:25</td>
                    <td>192.168.1.1</td>
                    <td>192.168.1.2</td>
                    <td>TCP</td>
                    <td>Sample Payload Data</td>
                </tr>
               
                    
                    <tr>
                        <td>12:30:25</td>
                        <td>192.168.1.1</td>
                        <td>192.168.1.2</td>
                        <td>TCP</td>
                        <td>GET / HTTP/1.1</td>
                    </tr>
                    
                   
                    <tr>
                        <td>12:31:45</td>
                        <td>10.0.0.5</td>
                        <td>10.0.0.10</td>
                        <td>UDP</td>
                        <td>DNS Query: www.example.com</td>
                    </tr>
                    
                 
                    <tr>
                        <td>12:32:10</td>
                        <td>172.16.0.100</td>
                        <td>8.8.8.8</td>
                        <td>ICMP</td>
                        <td>Ping Request</td>
                    </tr>
                    
                    
                    <tr>
                        <td>12:33:55</td>
                        <td>192.168.1.10</td>
                        <td>192.168.1.12</td>
                        <td>TCP</td>
                        <td>POST /login HTTP/1.1</td>
                    </tr>
                    
                    
                    <tr>
                        <td>12:35:20</td>
                        <td>10.1.1.50</td>
                        <td>172.217.12.174</td>
                        <td>HTTPS</td>
                        <td>Encrypted Payload</td>
                    </tr>
                </tbody>
        </table>
    </div>
</body>
</html>
