# Creative Solution Design

#### 3. Creative Solution Design
- **Solution Overview**
    - Users connect their wallets via MetaMask.
    - Users input a seven-digit number and specify the number of tickets to purchase.
    - Users then pay for the lottery tickets. Each ticket costs 0.001 ETH. The total cost is the ticket price multiplied by the number of tickets.
    - The lottery is drawn every three days from the deployment time.
    - The winning number is generated based on the timestamp and a random number.
    - After the winning number is determined, it is compared with all tickets purchased within the three-day period. Winners are directly awarded their prizes.
    - The funds from ticket purchases are split into two parts: half goes to the first prize pool, and the other half is used for operational costs and to fund the second, third, and fourth prizes.
    - If no one wins the first prize, the prize pool continues to accumulate. If only one person wins the first prize, they receive the entire first prize pool. If multiple people win, the first prize pool is distributed proportionally based on the number of winning tickets held.
    - The second prize is 2 ETH, the third prize is 1 ETH, and the fourth prize is 0.5 ETH.
    - A ticket with a number that exactly matches the winning seven-digit number wins the first prize. A ticket with one digit different wins the second prize, two digits different wins the third prize, and three digits different wins the fourth prize. If multiple winning tickets are purchased, the prize is multiplied by the number of winning tickets.