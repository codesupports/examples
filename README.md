
 <pre> <p><input type="radio" value="red" name="form" 
            id="one" onclick="myFunction(this.id)"/> Red</p>
  <p><input type="radio" value="Green"  name="form" 
            id="two" onclick="myFunction(this.id)"/> Green</p>
  <p><input type="radio" value="blue" name="form" 
            id="three" onclick="myFunction(this.id)"/> Blue</p></pre>
  
  <div id="container">Change the border color of div according to the radio button</div>
  
  <script>
  
  function myFunction(id) {
    document.getElementById("container").style.borderColor = document.getElementById(id).value;
}
  
</script>

