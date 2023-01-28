function sentenceToUpperCase(sentenceInput) {
  if (typeof sentenceInput === 'string') {
    let arrayStrLower = sentenceInput.split(' ');
    let arrayStrUpper = sentenceInput.split(' ');

    arrayStrUpper = arrayStrUpper.map(function (x) {
      return x.toUpperCase();
    });

    arrayStrLower = arrayStrLower.map(function (x) {
      return x.toLowerCase();
    });

    let counter = 2;
    let finalArray = [];
    for (let i = 0; i < sentenceInput.length; i++) {
      if (counter % 2 == 0) {
        finalArray.push(arrayStrLower[i]);
      }
      if (counter % 2 == 1) {
        finalArray.push(arrayStrUpper[i]);
      }

      counter++;
    }

    console.log(finalArray.join(' '));
  } else {
    console.log('The input is not a string');
  }
}

sentenceToUpperCase('Ala ma kota');
sentenceToUpperCase('tescik');
sentenceToUpperCase('Raz dwa trzy CZTERY');

module.exports = sentenceToUpperCase;
