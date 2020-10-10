day02作业：

第一题：

let Mark_height = 1.85,Mark_mass = 68;

let John_height = 1.83,John_mass = 63;

let Mark_BMI = Mark_mass / (Mark_height * Mark_height);

let John_BMI = John_mass / (John_height * John_height);

console.log("Mark BMI值：",Mark_BMI);

console.log("John BMI值：",John_BMI);

let compare;

compare = (Mark_BMI > John_BMI) ? true : false;

console.log(compare);

console.log("Mark的BMI是否比John的更高？",String(compare));



第二题：

//Mike和John的比赛

let JohnAvg = (89 + 120 + 103) / 3;

let MikeAvg = (116 + 94 + 123) / 3;

console.log("John队伍的平均分是："+JohnAvg+"\n" + "Mike队伍的平均分是："+MikeAvg+"\n")

if(JohnAvg > MikeAvg){

 console.log("John队伍获胜！" + "John队伍的平均分是："+JohnAvg);

}

else if (MikeAvg>JohnAvg){  

 console.log("Mike队伍获胜！" + "Mike队伍的平均分是："+MikeAvg);

}

else{  

 console.log("平局！");

}



//改分数

let JohnAvg1 = (121 + 122 +123) / 3;

let MikeAvg1 = (131 + 120 +110) / 3;

console.log("John队伍的平均分是："+JohnAvg1+"\n" + "Mike队伍的平均分是："+MikeAvg1+"\n")

if(JohnAvg1 > MikeAvg1){  

console.log("John队伍获胜！" + "John队伍的平均分是："+JohnAvg1);

}

else if (MikeAvg1>JohnAvg1){  

console.log("Mike队伍获胜！" + "Mike队伍的平均分是："+MikeAvg1);

}

else{  

 console.log("平局！");

}







//三人队伍比赛

let JohnAvg = (89 + 120 + 103) / 3;

let MikeAvg = (116 + 94 + 123) / 3;

let MaryAvg = (97 + 134 + 105) / 3;

console.log("John队伍的平均分是："+JohnAvg+"\n" + "Mike队伍的平均分是："+MikeAvg+"\n" + "Mary队伍的平均分是："+MaryAvg+"\n")

if((JohnAvg > MikeAvg) && (JohnAvg > MaryAvg)){

 console.log("John队伍获胜！" + "John队伍的平均分是："+JohnAvg);

}

else if ((MikeAvg>JohnAvg) && (MikeAvg>MaryAvg)){  

 console.log("Mike队伍获胜！" + "Mike队伍的平均分是："+MikeAvg);

}

else if((MaryAvg>JohnAvg) && (MaryAvg>MikeAvg)){ 

 console.log("Mary队伍获胜！" + "Mary队伍的平均分是："+MaryAvg);

}

else{  

 console.log("平局！");

}



//改分数

let JohnAvg2 = (111 + 122 +133) / 3;

let MikeAvg2 = (101 + 110 +111) / 3;

let MaryAvg2 = (123 + 134 +100) / 3;

console.log("John队伍的平均分是："+JohnAvg2+"\n" + "Mike队伍的平均分是："+MikeAvg2+"\n" + "Mary队伍的平均分是："+MaryAvg2+"\n")

if((JohnAvg2 > MikeAvg2) && (JohnAvg2 > MaryAvg2)){  

console.log("John队伍获胜！" + "John队伍的平均分是："+JohnAvg2);

}

else if ((MikeAvg2>JohnAvg2) && (MikeAvg2>MaryAvg2)){  

console.log("Mike队伍获胜！" + "Mike队伍的平均分是："+MikeAvg1);

}

else if((MaryAvg2>JohnAvg2) && (MaryAvg2>MikeAvg2)){  

console.log("Mary队伍获胜！" + "Mary队伍的平均分是："+MaryAvg2);

}

else{  

 console.log("平局！");

}



第三题：

let all ="";

for(let i=1; i<=4; i++){  

let blank = " ";  

let stars = " ";  

for(let m = 1; m <= 4-i; m++){

blank = blank + " ";

 }

for(let n=1; n<=i;n++){

 stars = stars + "*" + " ";

 }  

 all = all +blank + stars +"\n";

 }

 for(let i=4-1; i>0; i--){  

 let blank = " ";  

 let stars = " ";  

 for(let m=1; m<=4-i; m++){    

 blank += " ";  

 }  

 for(let n=1; n<=i; n++){    

 stars += "*" + " ";  

 }   

 all += blank + stars + "\n";}console.log(all);





