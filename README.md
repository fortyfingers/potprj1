# potprj1
pot legality prj using buttons
<!DOCTYPE html>
<html>
<body>

<p>Input your age and click the button:</p>

<input id="age" value="18" />

<button onclick="myFunction()">Try it</button>

<p id="demo"></p>

<script>
function myFunction() {
  var age, voteable;
  age = document.getElementById("age").value;
  voteable = (age < 18) ? "Too young":"Old enough";
  document.getElementById("demo").innerHTML = voteable + " to vote.";
}
</script>


<p> input age to see if you can drink legally </p>

<input id="ages" value="21" />

<button onclick="myFun()">Click Me</button>

<p id="dem"></p>
<script>
function myFun() {
  var ages, legal;
  ages = document.getElementById("ages").value;
  legal = (ages < 21) ? "Too young":"Old enough";
  document.getElementById("dem").innerHTML = legal + " to consume booze";
}
</script>
</body>
</html>
