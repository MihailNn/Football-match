# Football-match
//If the guessed outcome of the match return1. if guessing the score return 2
const check = (a, b, c, d) => {
  if (a == c && b == d) {
    return 2;
  }
  else if ((a === b && c == d) || (a < b && c < d) || (a > b && c > d)) {
    return 1;
  }
  else {
    return 0;
  }
};
