# Activity-2
Use CSS to recreate these buttons from famous websites.  all buttons must be in one composition. upload your repository in GitHub

<!DOCTYPE html>
<html>

<head>
<title>ACTIVITY 2</title>

<style>

  body {
    background-color: Pink;
    font-family: Arial;
    color: white;
    padding: 20px;
  }


 .three-space {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  gap: 40px;
  margin: 40px;
  width: auto;

}

 .two-space {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 40px;
  margin: 50px;
  width: auto;

}

  .Uber-button {
    background-color: rgb(0, 0, 0);
    color: white;
    border: 2px solid white;
    padding: 14px 26px;
    cursor: pointer;
  }


  .Amazon-button {
    background-color: rgb(255,216,20);
    color: rgb(0, 0, 0);
    padding: 12px 50px;
    border-radius: 25px;
    cursor: pointer;
  }
  .GitHub-button {
    background-color: rgb(46,164,79);
    color: rgb(255, 255, 255);
    padding: 12px 20px;
    border-radius: 6px;
    font-weight: bold;
    cursor: pointer;
  }

  .Bootstrap-get {
    background-color: rgb(121,82,179);
    color: rgb(255, 255, 255);
    padding: 12px 20px;
    border-radius: 6px;
    font-weight: bold;
    cursor: pointer;
  }

  .Bootstrap-download {
    background-color: rgb(108,117,125);
    color: rgb(255, 255, 255);
    border: 2px solid rgb(121,82,179);
    padding: 12px 20px;
    border-radius: 5px;
    cursor: pointer;
  }

  .LinkedIn-apply {
    background-color: rgb(10,102,194);
    color: rgb(255, 255, 255);
    padding: 14px 30px;
    border-radius: 25px;
    font-weight: bold;
    width: 260px;
    text-align: center;
    cursor: pointer;
  }

  .LinkedIn-save {
    background-color: rgb(255, 255, 255);
    color: rgb(10,102,194);
    border: 2px solid rgb(10,102,194);
    padding: 12px 20px;
    border-radius: 25px;
    font-weight: bold;
    cursor: pointer;
  }


</style>
</head>
<body>

  
   <div class="three-space">
  <div>
    <h3>2a. Uber</h3>
    <button class="Uber-button">Request now</button>
  </div>

  <div>
    <h3>2b. Amazon</h3>
    <button class="Amazon-button">Add to Cart</button>
  </div>

  <div>
    <h3>2c. GitHub</h3>
    <button class="GitHub-button">Sign up</button>
  </div>
</div>
  
  <div class="two-space">
      <div>
    <h3>2d. Bootstrap</h3>
    <button class="Bootstrap-get">Get started</button>
    <button class="Bootstrap-download">Download</button>
  </div>

  <div>
    <h3>2e. LinkedIn</h3>
    <button class="LinkedIn-apply">Apply on company website</button>
    <button class="LinkedIn-save">Save</button>
  </div>
  </div>
  </div>

</body>
</html>
