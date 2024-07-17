# FSWDT3
DAY3
<!DOCTYPE html>
<html>
    <head>
        <title>Table and tags</title>
        <style>
            table,td,th{
                border:2px solid red;
                border-collapse: collapse;
            }
        </style>
    </head>
    <!-- <center> -->
    <body>
            <h4>insta login page </h4>
            <!-- input tag -->
            <label>User name</label>
            <input type="text" placeholder="pls enter ur user name" required/>
            <label>Password:&nbsp;</label>
            <input type="password" placeholder="pls enter ur password" required/>
            <label>Gender:&nbsp;&nbsp;&nbsp;&nbsp;</label>
            <input type="radio" name="gender"/><label>male</label>
            <input type="radio" name="gender"/><label>Female</label>
            <input type="radio" name="gender"/><label>P N s</label>

<hr/>
        <table border="2" style="border-collapse: collapse;">
        <tr>
            <th>Company Name</th>
            <th>Mail id</th>
            <th>Phone Number</th>
        </tr>
        <br/>
        <tr>
            <!-- Rowspan -->
            <td rowspan="1">Isro</td>
            <!-- colspan -->
            <td colspan="2">abcisro@gmail.com</td>
            <td>234545675</td>
        </tr>
        <br/>
        <tr>
            <td>NASA</td>
            <td>xyznasa@gmail.com</td>
            <td>54643883478</td>
        </tr>
        <br/>
        <tr>
            <td>Dhanushkul</td>
            <td>mnodhanush @gmail.com</td>
            <td>3422355522</td>
        </tr>
    </table>
    </body>
<!-- </center> -->
</html>
