# WINOLI140_SOZ2301_Nwabisa_WinstonStephenOliver_IWA_6

Challenge 1 

const primaryPhone = 'O748105141'
const secondaryPhone = '0219131568'

// Only change below this line

const primaryValid = typeof number == primaryPhone 
const secondaryValid = typeof number !== secondaryPhone

console.log('Primary phone is valid numerical string:', Boolean (primaryValid));
console.log('Secondary phone is valid numerical string:', Boolean (secondaryValid ));

Challenge 2 

const rent = 400;
const tax = '12%';
const food = 51.7501;
const salary = 800;
const transport = 10.2;
const hourOfDay = 00;
const minuteOfDay = 00;

// Only change below this line

if ((hourOfDay !== null) && (minuteOfDay !== null) && (hourOfDay == '00') && (minuteOfDay == '00')) {
	const taxAsDecimal = parseInt(tax) / 100;
    const startingAfterTax = salary * (1.04051 - taxAsDecimal)
	const balance = startingAfterTax - transport - food - rent

    console.log('R'+ balance.toFixed(2))

}
