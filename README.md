# EmployeeCount.SQL
MySQL work-in-progress to count &amp; order employees by company id




const times = regExp("16:00:00")
    let splitReadings = RegExp(times, "");
    let newArr = [];
    
    while(splitReadings < 251){
        for (let i = 1; i < 251; i++){
            if (splitReadings[i].includes("Missing")){
                let value = splitReadings.indexOf(i - 1) + readings.indexOf(i + 1)/20;
                newArr.push(i);
                console.log(newArr)
            }
        }
    }

function calcMissing(readings) {
    let newArr = []
    for (let counter = 0; counter < 251; i++){
            let decimal = (parseFloat([counter]));
            let value = readings.indexOf(i - 1) + readings.indexOf(i + 1)/20;
            if(i.includes('Missing')){
                newArr.push(value);
        }
    }    
};

Output
32.69
32.15
32.61
29.3
28.96
28.78
31.05
29.58
29.5
30.9
31.26
31.48
29.74
29.31
29.72
28.88
30.2
27.3
26.7
27.52

Input
250
1/3/2012 16:00:00	26.96
1/4/2012 16:00:00	27.47
1/5/2012 16:00:00	27.728
1/6/2012 16:00:00	28.19
1/9/2012 16:00:00	28.1
1/10/2012 16:00:00	28.15
1/11/2012 16:00:00	27.98
1/12/2012 16:00:00	28.02
1/13/2012 16:00:00	28.25
1/17/2012 16:00:00	28.65
1/18/2012 16:00:00	28.4
1/19/2012 16:00:00	28.435
1/20/2012 16:00:00	29.74
1/23/2012 16:00:00	29.95
1/24/2012 16:00:00	29.5703
1/25/2012 16:00:00	29.65
1/26/2012 16:00:00	29.7
1/27/2012 16:00:00	29.53
1/30/2012 16:00:00	29.62
1/31/2012 16:00:00	29.7
2/1/2012 16:00:00	30.05
2/2/2012 16:00:00	30.17
2/3/2012 16:00:00	30.4
2/6/2012 16:00:00	30.22
2/7/2012 16:00:00	30.485
2/8/2012 16:00:00	30.67
2/9/2012 16:00:00	30.8
2/10/2012 16:00:00	30.8
2/13/2012 16:00:00	30.77
2/14/2012 16:00:00	30.46
2/15/2012 16:00:00	30.39
2/16/2012 16:00:00	31.55
2/17/2012 16:00:00	31.32
2/21/2012 16:00:00	31.61
2/22/2012 16:00:00	31.68
2/23/2012 16:00:00	31.59
2/24/2012 16:00:00	31.5
2/27/2012 16:00:00	31.5
2/28/2012 16:00:00	31.93
2/29/2012 16:00:00	32
3/1/2012 16:00:00	32.39
3/2/2012 16:00:0{-truncated-}

function calcMissing(readings) {
    let decReadings = [];
    
    for (let i = 1; i < 251; i++){
        if (readings[i].includes("Missing")){
            let value = readings/20;
            
            let readingSplice = readings.splice(i,1,value);
            let readingsToStrng = readingSplice.toString();
            let newReadings = 
                readingsToStrng.replaceAll(':', " ");
                readingsToStrng.replaceAll('/', '');
            
            let decimals = parseFloat(newReadings[i])
            decReadings.push(decimals);
        }   
    }  
}// Write your code here
            newReadings.forEach(reading) (readings)=>{
            let decimals = parseFloat(newReadings[i])
            decReadings.push(decimals);
            }
        }   
    }  


function calcMissing(readings) {
    let eachString= [];

        readings.forEach(reading => let readingSplice = readings.splice(i,1,value));
	readingSplice.forEach(splice => splice.toString()eachString.push());
	
	for( let i = 0; i <= 250; i++){
		if eachString[i].includes("Missing")){
			readings.splice(i,1,value);
            		let value = (i - 1) + (i + 1)/20;
	}
