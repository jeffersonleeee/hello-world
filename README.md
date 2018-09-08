# Function 
 Today is Wednesday.
declaration if functions

function monday(day){
  return day * (3/2);
};

function tuesday(day2){
  return monday(day2) + 100;
};

console.log(tuesday(1));

function step1(upper,down){
  return upper + down;

};

function step2(multiply,multiply2){
  return step1(multiply,multiply2) * 20
  
};



function step3(devided,devided2){
  return step2(devided,devided2) * (1/2);
}

console.log(step3(100,200));
