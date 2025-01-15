# table_html_css
Hi-Kod Front-End Atölyesi ödev-1
<!DOCTYPE html>
<html>
  <table>
    <style>
      table {
                font-family: 'Times New Roman', Times, serif;
                border-radius: 5px;
                width: 100%;
                border-collapse: collapse;
            }
            th {
                background-color: beige;
                border-color: black;
                border-width: 5;
                border-style: double;
                color: cadetblue;
                padding: 10 px;
            }
            td {
                font-style: italic;
                border-width: 15;
            }
            th:nth-child(even),td:nth-child(even) {
                background-color: rgba(150, 212, 212, 0.4);
            }
        </style>
        <tr>
          <th>Name</th>
          <th>Surname</th>
          <th>School Number</th>
          <th>Departmen Name</th>
          <th>Phone Number</th>
        </tr>
        <tr>
          <td>Alfreds</td>
          <td>Futterkiste</td>
          <td>12345</td>
          <td>Philosophy</td>
          <td>05442218823</td>
        </tr>
        <tr>
          <td>Frank</td>
          <td>Patrickson</td>
          <td>23456</td>
          <td>Management</td>
          <td>05232425627</td>
        </tr>
        <tr>
          <td>Lisa</td>
          <td>Robert</td>
          <td>34567</td>
          <td>Information Systems</td>
          <td>05232333627</td>
        </tr>
      </table>
</html>
