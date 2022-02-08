let name = "Aman"

let add = 8 + 9

let sub = 56 - 39

let div = 60/12

let a = 13*9

/**
 * Returns a letter grade.
 * "A": 90-100%
 * "B": 80-89%
 * "C": 70-79%
 * "D": 60-69%
 * "F": 0-59%
 * @param {number} score
 * @param {number} total maximum possible score
 * @return {string} the score represented as a letter grade
 */

 const grade = (score) =>{
  if (score >=90 && score <= 100) {
    return "A";
  } else if (score >= 80 && score < 90) {
    return "B";
  } else if (score >= 70 && score < 80) {
    return "C";
  } else if (score >= 60 && score < 70) {
    return "D";
  } else if (score >= 0 && score <= 59) {
    return "F";
  } else {
    return "enter score between 0 to 100";
  } 
};


