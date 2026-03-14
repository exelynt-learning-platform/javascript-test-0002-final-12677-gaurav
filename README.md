
let num = 5;

for (let i = 0; i < num; i++) {

  let row = "";

  for (let j = 0; j < i; j++) {
    row += " ";
  }

  let value = 4 - i;

  for (let j = 0; j < num - i; j++) {

    if (j === 0 || j === num - i - 1) {
      row += "1 ";
    } 
    else if (i === 0 && j === 2) {
      row += "6 ";
    } 
    else {
      row += value + " ";
    }

  }

  console.log(row);
}

