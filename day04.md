### day04

1.创建一个简单的小费计算器函数（tipCalculator）分别是124元、48元和268元。如果账单小于50，给20%作小费，50-100之间给15%，超过200给10%。

1）包含三个小费  2）包含所有三个最终支付金额（账单加小费）

```
//01 bill
const tipCalculator = bills => {
    const tips = []
    const costs = []
    bills.forEach(bill =>{
    let tip;
    if (bill < 50){
    tip = bill * 0.2
    }else if (bill >= 50 && bill <= 200){
    tip = bill * 0.15
    }else{
    tip = bill * 0.1
    }
    const cost = bill + tip
    tips.push(tip)
    costs.push(cost)
    })
    console.log(tips,costs)
    }
    tipCalculator([124,48,268]);
```



2.假设有三个数a、b、c,求这三个数的平均值的函数为:

function mean(a, b，c) {return(a+b+c)/3;}

1)如果要求任意个数的数字的平均值，该如何改进这个函数呢?请编写改进的mean1() |函数，让该函数可以计算任意个数的数字的平均值。

提示:使用扒展运算符

●2)请编写函数[ mean2()]， 使用数组的reduce() 函数改写mean1()，让代码更佳精简。

●3)请在第二步的基础上编写函数mean3() )， 实现只对数组中的偶数求平均值。提示: 使用回调函数和map()。

```
//02 mean 1)
function mean1() {
    var l=arguments.length;
    var sum=0;
    for(var i=0;i<=l;i++){
        sum+=i;
    }
    var Avg=sum/l;
    console.log(Avg);
    return (Avg);   
}

     //2)
```

