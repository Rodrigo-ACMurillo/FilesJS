function drawImage(){
    var ctx = $("canvas")[0].getContext("2d"),
        img = new Image();
    
    img.onload = function(){
        ctx.drawImage(img, 0, 0, 500, 500);
    };
    img.src = "http://photojournal.jpl.nasa.gov/jpeg/PIA17555.jpg";
    $("addSpan").text("Cargando...");
    document.getElementById("canvas").style.display="block";
}

function eraserImage(){
		 document.getElementById("canvas").style.display="none";
}

$("#add").click(drawImage);
$("#eraser").click(eraserImage);
