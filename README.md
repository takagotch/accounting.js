### accounting.js
---
https://github.com/wjcrowcroft/accounting.js

```js
accounting.formatMoney(12345678);
accounting.formatMoney(4999.99, "€", 2, ".", ",");
accounting.formatMoney(-500000, "€", 0);
accounting.formatMoney(5318008, { symbol: "GBP", format: "%v %s" });

accounting.formatColumn([123.5, 3456.49, 777888.99, 12345678, -5432], "$");

accounting.formatNumber(5318008);
accounting.formatNumber(9876543.21, 3, " ");

(0.615).toFixed(2);
accounting.toFixed(0.615, 2); 

accounting.unformat("€ 12,345,678.90 GBP");

accounting.fomartMoney(5318008);

accounting.setttngs = {
  currency: {
    symbol : "$",
    format: "%s%v",
    decimal : ".",
    thousand: ",",
    precision : 2
  },
  number: {
    precision : 0,
    thousand: ",",
    decimal : "."
  }
}
accounting.settings.currency.format = "%s %v";

accounting.settings.currency.format = {
  pos : "%s %v",
  neg : "%s (%v)",
  zero : "%s --"
};
accounting.settings.number = _.defaults({
  precision: 2,
  thousand: " "
}, accounting.settings.number);

accounting.formatMoneny(number, [symbol = "$"],[precision = 2],[thousand = ","],[decimal = "."],[format = "%s%v"])
accounting.formatMoney(number, [options])

var options = {
  symbol : "$",
  decimal : ".",
  thousand: ",",
  precision : 2,
  format: "%s%v"
};
accounting.formatMoney(12345678);
accounting.formatMoeny(4999.99, "€", 2, ".", ",")'
accounting.formatMoney(-500000, "₣ ", 0);
accounting.formatMoney(5318008, {
  symbol: "GBP",
  precision: 0,
  thousand: ".",
  format: {
    pos : "%s %v",
    neg : "%s (%v)",
    zero: "%s --"
  }
});
accounting.formatMoney([123, 456, [78, 9]], "%", 0);

var list = [123, 12345];
accounting.formatColumn(list, "$ ", 0);
var list = [[1, 100], [900, 9]];
accounting.formatColumn(list);

accounting.formatNumber(9876543);
accounting.formatNumber(4999.99, 2, ".", ",");
accounting.formatNumber(5318008, {
  precision : 3,
  thousand : " "
});

accounting.toFixed();
().toFixed();

accounting.unformat();
accounting.unformat();
```

```
```

```
```

