A lightweight, fast, and reliable currency conversion package for Node.js with real-time exchange rates.

## **Installation** 
_npm i currcon_

## **Quick Start**

### **javascript** 

```
import currencyConverter from "currcon"
currencyConverter("KRW", "INR", 5).then(res=>console.log(res));
```


### **API Reference**
```
currencyConverter(fromCurrency, toCurrency, units)
```
Converts an amount from one currency to another.

### **Parameters**
- fromCurrency (string): The currency to convert from.(e.g.,'USD')
- toCurrency (string): The currency to convert to.(e.g.,'INR')
- units (int): The amount to be converted

### **Returns**
Promise<number>: The converted amount