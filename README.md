js-calculate
============
<!DOCTYPE html>
<head>
    <title>calculator tesssssst</title>
   
</head>
<body>
    <form>
        <div>
            <br></br>
            <label for="input1">input number</label>
            <input type="number"  id="input1"/>
        </div>
        <br></br>
        <div>
            <label for="input2">input number</label>
            <input type="number"  id="input2"/>
        </div>
        <br></br>
    
        <div>
            <button id="add">
                add
            </button>
             <button id="subtract">
                subtract
            </button>
              <button id="multiply">
                multiply
            </button>
               <button id="divide">
                divide
            </button>
        </div>
        
    </form>
    
    <script type="text/javascript">
        var x=document.getElementById("input1").value;
        var y=document.getElementById("input2").value;
        
        //define four basic function
       
        var ad=function(){
            var z=x+y;
            alert(z);
            
        }
        var sub=function(){
            var z=x-y;
            alert(z);
        }
        var mult=function(){
            var z=x*y;
            alert(z);
        }
        var div=function(){
            var z=x/y;
            alert(z);
        }
        
        document.getElementById("add").addEventListener("click",ad,false);
        document.getElementById("subtract").addEventListener("click",sub,false);
        document.getElementById("multiply").addEventListener("click",mult,false);
        document.getElementById("divide").addEventListener("click",div,false);
    
       
       
          
    </script>
</body>
</html>
