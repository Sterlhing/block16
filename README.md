# block16

/*

discounts:

if (customer has subscription) {
  price = price * 0.75;
}

if (cusomer has discount) {
  price = price - 10;
}

return `your grand total is ${price}`;


};

const timmy = {
  prescription: "acetaminophen",
  pricePerRefill: 25,
  refills: 3,
  subscription: false,
  coupon: true,
};

const sarah = {
  prescription: "diphenhydramine",
  pricePerRefill: 50,
  refills: 1,
  subscription: true,
  coupon: false,
};

const rocky = {
  prescription: "phenylephrine",
  pricePerRefill: 30,
  refills: 5,
  subscription: true,
  coupon: true,
};

console.log(calculatePriceForPrescription(timmy));
console.log(calculatePriceForPrescription(sarah));
console.log(calculatePriceForPrescription(rocky));
