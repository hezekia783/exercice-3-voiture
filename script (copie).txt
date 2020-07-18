var maVoiture = document.querySelector('.voiture')
var positionInitiale = maVoiture.style.left;

function faireBouger(direction){
positionInitiale = +positionInitiale + direction ;
document.querySelector('.voiture').style.left = positionInitiale + 'px';
}
var positionInitiale2 = maVoiture.style.transform;


function faireRoter(rotation){
    positionInitiale2 = +positionInitiale2 + rotation;
    document.querySelector('.voiture').style.transform = 'rotate('+positionInitiale2 + 'deg)';
}


