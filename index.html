<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        *{
            font-family: sans-serif;
            background: #1f3040;  
        }
    </style>
</head>
<body>
    <div style="margin:auto;text-align:center;justify-content: center; width:50%; margin-top: 100px;">
         <h2 style="color:white">Enter the number :-</h2>
         <input type="text" id="number" 
                size="70" 
                style="background-color:white"
                onkeyup="updating();"
                onkeydown="return 
                        (event.ctrlKey 
                         event.altKey 
                         (47<event.keyCode && event.keyCode<58 && event.shiftKey==false) 
                         (95<event.keyCode && event.keyCode<106)
                         (event.keyCode==8)  (event.keyCode==9) 
                         (event.keyCode>34 && event.keyCode<40) 
                        || (event.keyCode==46) 
                        )"
         />
                        <br/>
                        <br/>
                        <br/>

        <h1 id="box" style="color:rgb(8, 228, 19)">Here number into string</h1>
    </div>
</body>
</html>



<script>
    function updating(){
    var String =   document.getElementById('number').value;

    var NumArry = new Array('', ' thousand',
     ' million', ' billion', ' trillion',
      ' quadrillion', ' quintillion');

    var final = new Array();
    var out = '';
    var String =   document.getElementById('number').value;
    
    if (String == '0') {
        document.getElementById('box').innerHTML = 'Zero';
        return;
    }

    if (String == 0) {
        document.getElementById('box').innerHTML = 'Please enter numbers';
        return;
    }

    var i = String.length;
    i = i - 1;

   
    while (String.length > 3) {
        var triDig = new Array(3);
        triDig[2] = String.charAt(String.length - 1);
        triDig[1] = String.charAt(String.length - 2);
        triDig[0] = String.charAt(String.length - 3);

        var varToAdd = triDig[0] + triDig[1] + triDig[2];
        final.push(varToAdd);
        i--;
        String = String.substring(0, String.length - 3);
    }
    final.push(String);
    final.reverse();

    
    for (j = 0; j < final.length; j++) {
        final[j] = Convert(parseInt(final[j]));
    }

    var bigScalCntr = 0; 

    for (b = final.length - 1; b >= 0; b--) {
        if (final[b] != "dontAddBigSufix") {
            final[b] = final[b] + NumArry[bigScalCntr] + ' , ';
            bigScalCntr++;
        }
        else {
            
            final[b] = ' ';
            bigScalCntr++;  
        }
    }
 
        for(n = 0; n<final.length; n++){
            out +=final[n];
        }

    document.getElementById('box').innerHTML = out;
    }

    
    function Convert(num){
        var ones = new Array('', ' one', ' two', ' three', ' four', ' five', ' six', ' seven', 
                            ' eight', ' nine', ' ten', ' eleven', ' twelve', ' thirteen', ' fourteen', ' fifteen', 
                            ' sixteen', ' seventeen', ' eighteen', ' nineteen');
        var tens = new Array('', '', ' twenty', ' thirty', ' forty', ' fifty', 
                           ' sixty', ' seventy', ' eighty', ' ninety');

        var hundred = ' hundred';

        var out = '';

        var String = num.toString();


        if (num == 0) {
            return 'dontAddBigSufix';
        }
       
        if (num < 20) {
            out = ones[num];
            return out;
        }

       
        if (String.length == 3) {
            out = ones[parseInt(String.charAt(0))] + hundred;
            out += tens[parseInt(String.charAt(1))];
            out += ones[parseInt(String.charAt(2))];
            return out;
        }
        out += tens[parseInt(String.charAt(0))];

        out += ones[parseInt(String.charAt(1))];

        return out;
    }   
</script>