# KENO ORACLE    
### Australian Keno Website Analysis System using PHP development as the directed access method - initially designed for Offline PHP usage, it has been adapted to work online using a random proxy recycler.
      
( proxy removed )

Uses official hidden Keno Website API,
```
// HISTORY,
$history_api="/v2/info/history";
// --------------- 
// LIVE DRAW, 
$live_api="/v2/games/kds";
// --------------- 
// TRENDING NUMBERS,
$trending_api="/v2/info/trends";
// ---------------
// HOT COLD
$hotcold_api="/v2/info/hotCold";
// ---------------
// JACKPOTS,
$jackpot_api="/v2/info/jackpots";

Example,
https://api-info-act.keno.com.au/v2/info/history?jurisdiction=act

```
## Installing     
* Edit the project to remove the Proxy Request method - that methods only for Heroku Example.       
* Start a local PHP server.    
* Launch locally.         
 
#### Heroku Deployment ( Worldwide Access Project )       
[![demo button](https://i.imgur.com/aaa86Vf.png)](https://noprox.herokuapp.com/) 
  
#### Deployment to Heroku
Create a FREE account first if you do not yet have one:     
https://signup.heroku.com/      
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

## History     
The KENO ORACLE was designed to educate people on methods that have been used by professional gamblers for years.   
    
A few years ago, my mother was extremely interested in methods to defeat the Keno system in Australia.      
She taught me this method amoung other methods that professional gamblers use to defeat gambling systems.
   
One of these methodologies she taught me will be discussed in this project, and a POC application that i slapped together for people to try out.   
   

This project was designed strictly for educational purposes only, it is NOT to be taken as gambling or financial advice under any circumstances - "I'm not Einstein, i make mistakes.",
    
####    Screenshot & Information      
![screen](IMG_20211111_015323.png)      
##### Oldest Number     
Answers the question of which number hasn't been drawn for the longest ?     
##### Game Depth    
How long has it been since that number came up, how many games was it  ?    
##### Probability of Depth        
This gives you your Probability Reading in an easy way to understand.       
  
>  If 1/4 = 0.25/1 Then 4 games = 100% of odds or ( x1 )      
   
#### Q/A            
> Q. Chart Has x7 on my number - Why ?    
 - The original chart shows how many occurrences of each number have been found in the game depth, however the new chart on the official website shows the game depth for each number.     
  
    
        

#### Using Information correctly ( method disclosed )    
• Keno games draw 20/80 numbers, that's 1/4 chances for every single number on the board.         
• A single number "One Spot" costs $1 and Pays $3, that's a $2 profit.      
• A single number "One Spot" has a 1/4 chance of winning (this is important for probability).   
• Let's do some math,          
    
Because the game pays $3 over a $1 bet, that means we can use a famous method by secret gamblers to always come out with profit.     
  
The famous method is to increase your bet amount, so much that the total cost of all your games will be less than the win amount if the game was to win - meaning the profit outweighs the total cost.     
   
##### How can you do that  ?    
> Several methods in existence work, but most methods are based on Arbitrage betting,    
> Let's say that you're flipping a coin for $1 and the win amount is $3 - Arbitrage betting is when you bet $1 on heads and $1 on tails - always walking away with the bookys money.     
 
> This (simplistic example) method is called - Arbitrage Betting.     
> We have a few ways when studying the KENO system in Australia to outwit the random system.      
   
> A am not a math wizard, so please bare with me....    
  
Here is Method 1 : the simplist way i could explain it.     
  
### METHOD 1    
DOUBLE ME BABY !!!            
This method requires you to double your bet every time you lose the game of 1 Spot with 1/4 chance.       

GAME : BET COST : WIN RESULT : WIN AMOUNT : TOTAL COST : PROFIT    
>  1 : $1 : 👎 : $0 : -$1 : +$0       
>  2 : $2 : 👎 : $0 : -$3 : +$0    
>  3 : $4 : 👎 : $0 : -$7 : +$0       
>  4 : $8 : 👍 : $24 : -$15 : +$9    
   
After losing 3 games and winning 1 game, using the double bet method allows you to always come out on top ( defeating the system ) - but be careful, doubling your bet over 21 times is more that 1 million dollars..             
       
   
### METHOD 2    
I LOVE THAT EVENS !!!           
This method requires you to keep betting on EVENS until you get a win, using the doubling method.   
   
( SAME CHART AS ABOVE )   

#### HOW DOES THIS WORK ?     
• We are reducing the game to a simple WIN or LOSE scenario - A WIN or LOSE scenario is the same as Heads or Tails     
• Here we have reduced the game to apply Arbitrage Betting on the simplified game.        


### Associated Projects                  
The project uses information from the following projects,       
####  Keno API        
https://github.com/JGolafshan/keno-api               
#### Active Proxy    
https://github.com/Empire-of-E-Projects/ActiveProxy     
#### GitPloyment      
https://github.com/Empire-of-E-Projects/Gitployment    

    
### Technology
* HTML    
* CSS    
* JavaScript    
* PHP   
