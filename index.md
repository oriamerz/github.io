<!DOCTYPE html>
<html lang="en">

<head>

  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.16.0/umd/popper.min.js"></script>
  <script src="https://kit.fontawesome.com/7d6a776ccf.js" crossorigin="anonymous"></script>

  <script src="main.js"></script>
  

  <style>
    .col-sm-2 {
      position: relative;
      max-width: 250px;
    }

    .col-sm-2 img {
      width: 100%;
      height: auto;
    }

    .popup {
      display: none;
      position: absolute;
      color: rgb(26, 4, 4);
      border: solid 1px rgb(17, 10, 41);
      background: rgb(245, 245, 245);
      text-align: right;
      width: 10%;
    }
  </style>
</head>

<body onload="fetchIssues()">

  <div class="container-fluid">
    <div class="row">
      <div class="col-sm-8">
        <div class="main_map" id="main_map1">div </div>
      </div>
      <div class="col-sm-2">
        <div id="issuesList">

        </div>
      </div>
    </div>
  </div>

</body>

</html>
