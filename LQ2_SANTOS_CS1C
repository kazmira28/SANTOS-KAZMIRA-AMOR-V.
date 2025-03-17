I. Code Transformation
I.1 Convert Conditional Statements to Conditional Ternary
a.
  (age >= 18 && genAverage >= 83) 
    ? console.log("You may enter College, under BSCS Program") 
    : console.log("Both conditions may have not met and not allowed to enroll");
b.
  (subject === "DSA" && grade >= 80) 
    ? console.log("You may enroll Application Development") 
    : (subject === "Math101" && grade <= 80) 
    ? console.log("You may enroll Calculus") 
    : console.log("You have to enroll DSA and pass to enroll AD and Math101 and pass to enroll Calculus");
I.2 Convert Conditional Ternary to Regular Conditional Statements
a.
  if (age >= 18) {
    console.log("You may now Register as a Voter for Elections 2025");
} else {
    console.log("You are too young to register as a voter for Elections 2025");
}
b.
  if (genAverage >= 85) {
    console.log("You may enroll in all Course Programs");
} else if (genAverage < 85 && genAverage > 82) {
    console.log("You may enroll in any Course Program except in CTE, SCJE, CHS");
} else {
    console.log("You may enroll in any Course Program except CTE, SCJE, CHS, CCS");
}
I.3 Convert For Loop to While Loop
a.
  let fname = "Jose Cruz";
let i = 0;

while (i < fname.length) {
    let c = 2 + i;
    let nLengthCounterTwo = fname.length - c;
    console.log(fname);
    console.log("Iterations Name was Printed: " + i);
    i++;
}
II. Code Snippet
Here’s the completed code snippet:
let registeredUsername = prompt("Register your Username");
let registeredPassword = prompt("Register your passcode");
let confirmPassword = prompt("Re-enter your passcode");

if (registeredPassword === confirmPassword) {
    alert("Congratulations! You have successfully registered.");

    let loginUsername = prompt("Username: ");
    if (loginUsername === registeredUsername) {
        let loginPassword = prompt("Password: ");
        if (loginPassword === registeredPassword) {
            alert("Welcome to DSA, " + loginUsername);
        } else {
            alert("Incorrect Password, Re-run the code!");
        }
    } else {
        alert("Incorrect Username, Re-run the code!");
    }
} else {
    alert("Password does not match, Re-run the code!");
}
III. Coding Problem
Here’s the source code for the described program:
let name = prompt("Enter your Name:");
let address = prompt("Enter your Address:");
let age = parseInt(prompt("Enter your Age:"));
let classRole = prompt("Enter your Class Role (Officer, Student, Teacher):");
let course = prompt("Enter your Course (BSCS, BSM, BAEL):");

if (course === "BSCS") {
    if (classRole === "Officer") {
        for (let i = 0; i < Math.floor(age / 4); i++) {
            console.log(`Name: ${name}, Role: Officer, Course: BSCS`);
        }
    } else if (classRole === "Student") {
        for (let i = 0; i < Math.floor(age / 4); i++) {
            console.log(`Name: ${name}, Role: Student, Course: BSCS`);
        }
    } else if (classRole === "Teacher") {
        for (let i = 0; i < Math.floor(age / 4); i++) {
            console.log(`Name: ${name}, Role: Teacher, Course: BSCS`);
        }
    } else {
        console.log("Default Role: Visitor");
    }
} else if (course === "BSM") {
    if (classRole === "Officer") {
        for (let i = 0; i < Math.floor(age / 4); i++) {
            console.log(`Name: ${name}, Role: Officer, Course: BSM`);
        }
    } else if (classRole === "Student") {
        for (let i = 0; i < Math.floor(age / 4); i++) {
            console.log(`Name: ${name}, Role: Student, Course: BSM`);
        }
    } else if (classRole === "Teacher") {
        for (let i = 0; i < Math.floor(age / 4); i++) {
            console.log(`Name: ${name}, Role: Teacher, Course: BSM`);
        }
    } else {
        console.log("Default Role: Visitor");
    }
} else if (course === "BAEL") {
    if (classRole === "Officer") {
        for (let i = 0; i < Math.floor(age / 4); i++) {
            console.log(`Name: ${name}, Role: Officer, Course: BAEL`);
        }
    } else if (classRole === "Student") {
        for (let i = 0; i < Math.floor(age / 4); i++) {
            console.log(`Name: ${name}, Role: Student, Course: BAEL`);
        }
    } else if (classRole === "Teacher") {
        for (let i = 0; i < Math.floor(age / 4); i++) {
            console.log(`Name: ${name}, Role: Teacher, Course: BAEL`);
        }
    } else {
        console.log("Default Role: Visitor");
    }
} else {
    console.log("Invalid Course Entered!");
  }
