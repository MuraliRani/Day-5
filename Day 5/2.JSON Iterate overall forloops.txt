//2.for the above JSON, iterate over all for loops(for,for in, for of, forEACH):

const ResumeData = {
    "Name": "Murali",
    "Title": "FullStack Developer",
    "Contact": {
      "Email": "muralideva443@gmail.com",
      "Phone": "6380527095",
      "Address": "2/363,V Ramasamy,Mallikapuram New Colony,Pilikkal Palayam(po),Paramathi velur(tk)",
      "Pincode":"637213"
    },
    "summary": "A Full Stack Developer is proficient in both front-end and back-end technologies, capable of developing complete web applications. They possess expertise in programming languages like HTML, CSS, and JavaScript for front-end development, while also being skilled in server-side scripting languages, databases, and frameworks like Node.js, Python, Ruby on Rails, or PHP for back-end development. Full Stack Developers are adept at creating responsive and user-friendly interfaces, managing databases, handling server-side logic, and ensuring the smooth functioning of applications from end to end.",
    "education": [
      {
        "Major":"10th",
        "school": "Government Higher Secondary School",
        "graduation_year": 2017
      },
      {
        "Major":"12th",
        "Group":"Maths Computer",
        "school": "Government Higher Secondary School",
        "graduation_year": 2019
      },
      {
        "Degree":"B.E",
        "Branch":"Computer Science and Engineering",
        "College":"Muthayammal College of Engineering",
        "graduation_year": 2023
      }
    ],
    "experience": [
      {
        "Title": "Technical Trainer",
        "company": "Terv and ByteXL",
        "location": "Chennai and Andhra Pradesh",
        "dates": "2022 - Present",
      },
    ],
    "skills": [
      "Java-FS",
      "Python",
      "C",
      "Html",
      "CSS",
      "Javascript",
      "Bootstrap",
      "MySql"
    ]
  };

  //Using for...in loop:
    for (let key in ResumeData) {
        console.log(key + ": ", ResumeData[key]);
    }

  // Using for...of loop for arrays (education and experience)
    for (let section of ResumeData.education) {
    console.log("Education: ", section);
    }

    for (let section of ResumeData.experience) {
        console.log("Experience: ", section);
      }



    // Using forEach for skills array:
    ResumeData.skills.forEach(skill => {
    console.log("Skill: ", skill);
    });





















