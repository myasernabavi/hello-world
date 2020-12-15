# hello-world
My first repository 
I am Mohammadyaser Nabavi and I love web programming and I am in the first of this way to be a good web developer.
 
 var myVar = setInterval(myTimer, 1000);

    function myTimer() {
        var d = new Date();
        document.getElementById("demo").innerHTML = d.toLocaleTimeString();
    }

    function Time() {
        tDate = new Date();
        tDate.setHours(17);
        tDate.setMinutes(23);
        tDate.setSeconds(55);
        tDate.setMilliseconds(500);
        tMillis = tDate - new Date();
        setTimeout(function () {
            setInterval(() => {
                console.log("salam");
            }, 1);  //Milisecond for repeat.
        }, tMillis)
        if (new Date().getMinutes() - tDate === 01) { return; }
    };






// This Project is made By MYN.
