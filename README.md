// learn about Arrays

// ---------Arrays[]--------

//let fruitchaat = ['apple','bannana','orange']
//console.log(fruitchaat);

//-------------push() --------Adds an element to the list

//fruitchaat.push('mango');
//console.log(fruitchaat);

//---------------pop()---------- Removes the last element from the list

//fruitchaat.pop();

//console.log(fruitchaat);

//------------concat([])------------

//fruitchaat = fruitchaat.concat(['kiwi','melon'])
//console.log(fruitchaat);

// Learn About Loops

// --------------While() Loops----------

//let i = 0;
//while (i <= 10){
  //console.log('fasting');
//i++;
//}

//-------- todo list -----------

//import inquirer from 'inquirer';

//let to_do_list = [];
//let condition = true;

///while(condition)
  
//{
//let addTask = await inquirer.prompt(
  //[
    
   //{
    // type : 'input',
   //  name : 'todo',
    // message : 'what do you want in todo list?',
//},
    
   // {
     // type : 'confirm',
     // name : 'addmore',
    //  message : 'Do you want to add more?',
     // default: 'false',
  //   }


    
//  ]
//);

//to_do_list.push(addTask.todo);
  //condition = addTask.addmore;
//console.log(to_do_list);
//}

// --------toUpperCase()----------

//let name: string = 'loyal';
//console.log(name.toUpperCase());
//console.log((name));

// --------toLowerCase()----------

//let name : string = 'LOYAL';
//console.log(name.toLowerCase());
//console.log(name);

// --------length----------

//let name : string = 'loyal';
//console.log(name.length);

// --------slice----------

 //is called indexnu   0123456789
//let name : string = 'javacsript is awesome';

//let fristChar = name.slice(0,10);

//let remaining = name.slice(10);

//fristChar = fristChar.toUpperCase();

//let combine = fristChar + remaining;
//console.log(combine);

//let name : string = 'javacsript is awesome';

//let fristChar = name.slice(0,14);

//let remaining = name.slice(14).toUpperCase();

//fristChar = fristChar.toLowerCase();

//let combine = fristChar + remaining;
//console.log(combine);

// --------trim()---------- use for remove white space

//let name : string = '   loyal   ';

//let print = name.trim();

//console.log(print);

//console.log(name);

// --------repeat()----------

//let name : string = 'loyal';

//let print = name.repeat(2);

//console.log(print);

// --------replace()----------

//let name : string = 'loyal';

//let print = name.replace('loyal','LOYAL');

//console.log(print);


// --------split()----------

//import promptSync from 'prompt-sync';

//const prompt = promptSync();

//let name = prompt('enter your name');//input javascript 

//let b = name.split('');

//console.log(b);

//output ['j','a','v','a','c','r','i','p','t']

// --------charAt()----------

//let name : string = 'loyal';

//let remain: string = name.slice(1);

//let print = name.charAt(0).toUpperCase();;

//console.log(print + remain);//output Loyal
