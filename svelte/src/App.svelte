
<style>
  #submit{
    border: 2px solid black;
    border-radius: 10px;
    padding: 2px 5px;
    color: black;
    font-weight: 500;
}

#title{
    color: rgb(126, 7, 244);
    font-weight: 600;
}

header{
    background-color: azure;
}

#project_code{
    border: 2px solid black;
    font-weight: 550;
}

#Zodiac_letters{
    color: black;
    font-weight: bold;
}

#output{
    font-weight: 500;
    color: black;
    padding: 20px 0px ;
  }
</style>

<main>
  <header class="text-gray-600 body-font">
    <link rel="stylesheet" href="https://unpkg.com/tailwindcss@^1.0/dist/tailwind.min.css">
        <div class="container mx-auto flex flex-wrap p-5 flex-col md:flex-row items-center">
            <a href="https://www.google.com/" class="flex title-font font-medium items-center text-gray-900 mb-4 md:mb-0">
                <svg xmlns="http://www.w3.org/2000/svg" fill="--" stroke="currentColor" stroke-linecap="round"
                    stroke-linejoin="round" stroke-width="2" class="w-10 h-10 text-white p-2 bg-indigo-500 rounded-full"
                    viewBox="0 0 24 24">
                    <path d="M12 2L2 7l10 5 10-5-10-5zM2 17l10 5 10-5M2 12l10 5 10-5"></path>
                </svg>
                <span class="ml-3 text-xl">Time Tool</span>
            </a>
            <nav
                class="md:mr-auto md:ml-4 md:py-1 md:pl-4 md:border-l md:border-gray-400	flex flex-wrap items-center text-base justify-center">
                <a href="https://www.google.com/" class="mr-5 hover:text-gray-900">Home</a>
                <a href="https://www.google.com/" class="mr-5 hover:text-gray-900">About</a>
                <a href="https://www.google.com/" class="mr-5 hover:text-gray-900">Services</a>
                <a href="https://www.google.com/" class="mr-5 hover:text-gray-900">Contact Us</a>
            </nav>
            <a href="https://github.com/PrathamAsrani/IEEE_Internship_Project" target="_blank">
                <button href="https://www.google.com/" id="project_code"
                    class="inline-flex items-center bg-gray-100 border-0 py-1 px-3 focus:outline-none hover:bg-gray-200 rounded text-base mt-4 md:mt-0">Project_Code
                    <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                        class="w-4 h-4 ml-1" viewBox="0 0 24 24">
                        <path d="M5 12h14M12 5l7 7-7 7"></path>
                    </svg>
                </button>
            </a>    
        </div>
    </header>
    <section class="text-gray-600 body-font">
      <div class="container mx-auto flex px-5 py-24 md:flex-row flex-col items-center">
          <div
              class="lg:flex-grow md:w-1/2 lg:pr-24 md:pr-16 flex flex-col md:items-start md:text-left mb-16 md:mb-0 items-center text-center">
              <h1 class="title-font sm:text-4xl text-3xl mb-4 font-medium text-gray-900" id="title">IEEE BOMBAY SECTION
                  <br class="hidden lg:inline-block">GROUP 55
              </h1>
              <p class="mb-8 leading-relaxed">The zodiac is a belt-shaped region of the sky that extends approximately
                  8?? north or south (as measured in celestial latitude) of the ecliptic, the apparent path of the Sun
                  across the celestial sphere over the course of the year. The paths of the Moon and visible planets
                  are within the belt of the zodiac.</p>
              <div class="flex justify-center">
                  <input type="date" id="myBirthday" value="dd-mm-yyyy">
                  <button id="submit" on:click={submitBirthday}>Submit</button>
              </div>
              <p>Your zodiac sign is : </p> <p id="output"></p>
          </div>  
          <div class="lg:max-w-lg lg:w-full md:w-1/2 w-5/6">
              <img class="object-cover object-center rounded" alt="hero"
                  src="https://www.logolynx.com/images/logolynx/2e/2eaec84e75333bf14596e8fa3ee66e68.png">
          </div>
      </div>
  </section>

<footer class="text-gray-600 body-font">
  <div class="container px-5 py-8 mx-auto flex items-center sm:flex-row flex-col">
    <a class="flex title-font font-medium items-center md:justify-start justify-center text-gray-900">
      <svg xmlns="http://www.w3.org/2000/svg" fill="--" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-10 h-10 text-white p-2 bg-indigo-500 rounded-full" viewBox="0 0 24 24">
        <path d="M12 2L2 7l10 5 10-5-10-5zM2 17l10 5 10-5M2 12l10 5 10-5"></path>
      </svg>
      <span class="ml-3 text-xl">IEEE BOMBAY SECTION</span>
    </a>
    <p class="text-sm text-gray-500 sm:ml-4 sm:pl-4 sm:border-l-2 sm:border-gray-200 sm:py-2 sm:mt-0 mt-4">?? 2023 Time Tool ???
      <a href="https://twitter.com/PrathamAsrani" class="text-gray-600 ml-1" rel="noopener noreferrer" target="_blank">@Pratham Asrani</a>
    </p>
    <span class="inline-flex sm:ml-auto sm:mt-0 mt-4 justify-center sm:justify-start">
      <a class="text-gray-500">
        <svg fill="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-5 h-5" viewBox="0 0 24 24">
          <path d="M18 2h-3a5 5 0 00-5 5v3H7v4h3v8h4v-8h3l1-4h-4V7a1 1 0 011-1h3z"></path>
        </svg>
      </a>
      <a class="ml-3 text-gray-500">
        <svg fill="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-5 h-5" viewBox="0 0 24 24">
          <path d="M23 3a10.9 10.9 0 01-3.14 1.53 4.48 4.48 0 00-7.86 3v1A10.66 10.66 0 013 4s-4 9 5 13a11.64 11.64 0 01-7 2c9 5 20 0 20-11.5a4.5 4.5 0 00-.08-.83A7.72 7.72 0 0023 3z"></path>
        </svg>
      </a>
      <a class="ml-3 text-gray-500">
        <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-5 h-5" viewBox="0 0 24 24">
          <rect width="20" height="20" x="2" y="2" rx="5" ry="5"></rect>
          <path d="M16 11.37A4 4 0 1112.63 8 4 4 0 0116 11.37zm1.5-4.87h.01"></path>
        </svg>
      </a>
      <a class="ml-3 text-gray-500">
        <svg fill="currentColor" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="0" class="w-5 h-5" viewBox="0 0 24 24">
          <path stroke="none" d="M16 8a6 6 0 016 6v7h-4v-7a2 2 0 00-2-2 2 2 0 00-2 2v7h-4v-7a6 6 0 016-6zM2 9h4v12H2z"></path>
          <circle cx="4" cy="4" r="2" stroke="none"></circle>
        </svg>
      </a>
    </span>
  </div>
</footer>
</main>

<script>
  // Created By Pratham Asrani

function submitBirthday() {
    let myBirthday = document.getElementById("myBirthday").value;
    // document.write(myBirthday); // create a new DOM not required
    // console.log(myBirthday);
    let arr;
    let year, month, day;
    arr = myBirthday.split("-");
    year = arr[0];
    month = arr[1];
    day = arr[2];
    // console.log(year);
    // console.log(month);
    // console.log(day);
    let yourZodiacSign = zodiacSign(day, month);
    // console.log(yourZodiacSign);
    document.getElementById("output").innerHTML = yourZodiacSign;
}

const zodiacSign = (day, month) => {
    let result = "";
    if (month == 3 && day >= 21) {
        // right
        result = "Aries : Aries people are very Ambitious";
    } else if (month == 4 && day <= 19) {
        // right
        result = "Aries : Aries people are very Ambitious";
    } else if (month == 4 && day >= 20) {
        // right
        result = "Taurus : You are a builder, restorer, and caretaker of those things you find important???primarily the earth, animals, and people.";
    } else if (month == 5 && day <= 20) {
        // right
        result = "Taurus : You are a builder, restorer, and caretaker of those things you find important???primarily the earth, animals, and people.";
    } else if (month == 5 && day >= 21) {
        // right
        result = "Gemini : Positive Qualities First of all, you're a great thinker. Many of the world's intellectuals are Geminis.";
    } else if (month == 6 && day <= 21) {
        // right
        result = "Gemini : Positive Qualities First of all, you're a great thinker. Many of the world's intellectuals are Geminis.";
    } else if (month == 6 && day >= 22) {
        // right
        result = "Cancer : Positive traits: Tenacity, dependability and persuasion";
    } else if (month == 7 && day <= 22) {
        // right
        result = "Cancer : Positive traits: Tenacity, dependability and persuasion";
    } else if (month == 7 && day >= 23) {
        // right
        result = "Leo : Leo Positive Traits: Good and Best Traits of this Zodiac Sign. Positive traits: generosity, aristocracy, chivalry, optimism";
    } else if (month == 8 && day <= 22) {
        // right
        result = "Leo : Leo Positive Traits: Good and Best Traits of this Zodiac Sign. Positive traits: generosity, aristocracy, chivalry, optimism";
    } else if (month == 8 && day >= 23) {
        // right
        result = "Virgo : Next of many positive Virgo traits is their neatness";
    } else if (month == 9 && day <= 22) {
        // right
        result = "Virgo : Next of many positive Virgo traits is their neatness";
    } else if (month == 9 && day >= 23) {
        // right
        result = "Libra : Librans is that they are sensitive and often care about others' feelings";
    } else if (month == 10 && day <= 23) {
        // right
        result = "Libra : Librans is that they are sensitive and often care about others' feelings";
    } else if (month == 10 && day >= 24) {
        // right
        result = "Scorpion : Scorpio has united many positive traits of the Water signs with the power given by ruling planets";
    } else if (month == 11 && day <= 21) {
        // right
        result = "Scorpion : Scorpio has united many positive traits of the Water signs with the power given by ruling planets";
    } else if (month == 11 && day >= 22) {
        // right
        result = "Sagittarius : Sagittarius loves (actually, needs) to try new things and have new experiences.";
    } else if (month == 12 && day <= 21) {
        // right
        result = "Sagittarius : Sagittarius loves (actually, needs) to try new things and have new experiences.";
    } else if (month == 12 && day >= 22) {
        // right
        result = "Capricornus : Capricorns are very strong emotionally, especially when achieving their goals as they don???t let anything distract them from getting ahead";
    } else if (month == 1 && day <= 19) {
        // right
        result = "Capricornus : Capricorns are very strong emotionally, especially when achieving their goals as they don???t let anything distract them from getting ahead";
    } else if (month == 1 && day >= 20) {
        // right
        result = "Aquarius : Open-mindedness. Almost every horoscope says that Aquarius personalities always try to consider new ideas.";
    } else if (month == 2 && day <= 18) {
        // right
        result = "Aquarius : Open-mindedness. Almost every horoscope says that Aquarius personalities always try to consider new ideas.";
    } else if (month == 2 && day >= 19) {
        // right
        result = "Pieces : Pisces Positive Traits Empathetic Pisces are extremely empathetic creatures with a lively imagination and a friendly disposition";
    } else if (month == 3 && day <= 20) {
        // right
        result = "Pieces : Pisces Positive Traits Empathetic Pisces are extremely empathetic creatures with a lively imagination and a friendly disposition";
    }
    return result;
};

</script>

