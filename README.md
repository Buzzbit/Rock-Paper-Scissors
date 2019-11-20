 function playerSelect(playerWeapon){
                let computerWeapon = computerSelect();
                if (playerWeapon == computerWeapon){
                    tie(playerWeapon, computerWeapon);
                }
                else if (
                    (playerWeapon === "Rock" && computerWeapon === "Scissors")||
                    (playerWeapon === "Paper" && computerWeapon === "Rock")||
                    (playerWeapon === "Scissors" && computerWeapon === "Paper"))
                {
                    win(playerWeapon, computerWeapon);
                }
            
                else {
                    lose(playerSelect, computerSelect)
                }
            }
