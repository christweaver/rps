
 function pcr(choice) {
    let computerChoice=null
    const random=Math.floor(Math.random()*3);
     if (random===0)
     {computerChoice='rock'}
     if (random===1)
     {computerChoice='paper'}
     if (random===2)
     {computerChoice='scissors'}
     console.log(computerChoice)

     if (choice==='rock' && computerChoice==='rock')
     {return 'its a tie'}

    if (choice==='rock' && computerChoice==='paper')
     {return 'paper beats rock, you lose'}

    if (choice==='rock' && computerChoice== 'scissors')
     {return 'rock beats scissors, you win'}

    if (choice==='paper' && computerChoice==='paper') 
    {return 'its a tie'}

    if (choice==='paper' && computerChoice==='rock') 
    {return 'paper beats rock, you win'}

     if (choice==='paper' && computerChoice==='scissors') 
     {return 'scissors beats paper, you lose'}

     if (choice==='scissors' && computerChoice==='scissors') 
     {return 'its a tie' }

     if (choice==='scissors' && computerChoice==='paper')
      {return 'scissors beats, paper you win'}

     if (choice==='scissors' && computerChoice==='rock') 
     {return 'rock beats scissors, you lose'}

 }
 let result=pcr('paper')
 console.log(result)
