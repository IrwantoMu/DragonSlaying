# DragonSlaying
another very basic and simple game
var slaying = true;
var youHit = Math.floor(Math.random() * 2);
var damageThisRound = Math.floor(Math.random()*5 + 1);
var totalDamage = 0;
var slaying = true;
while (slaying) {
    if (youHit) {
    console.log("you hit the dragon");
    totalDamage += damageThisRound; 
        if (totalDamage>=4) {
            console.log("you slew the Dragon");
        } else {
             youHit = Math.floor(Math.random() * 2);
        }
    
   } else {
        console.log("the dragon defeat you");
    }
    slaying = false;
};
