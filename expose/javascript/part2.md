1. At line 12, the value of i will be printed because var has no block-level visibility, so i's value can be used at line 12.
2. Line 13 will also print smoothly due to var's lack of block-level visibility.
3. Same as the first two - all of the variables are in the same function, so the console can read their values.

function discountPrices(prices, discount) {
    var discounted = [];
    var finalPrice = 0;

    for (var i = 0; i < prices.length; i++) {
        var discountedPrice = prices[i] * (1-discount);
        finalPrice = Math.round(discountedPrice * 100) / 100;
        discounted.push(finalPrice);
    }
    //console.log(i);
    console.log(discountedPrice);
    //console.log(finalPrice);
    return discounted;
}
discountPrices([100,200,300], 0.5);