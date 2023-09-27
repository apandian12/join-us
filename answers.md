- Who are you? What do you like building?
I am a self-starter with strong interpersonal skills. I work efficiently both as an individual contributor as well as along with a team.
------------------------------------------------------------------------------------------------
Do you own a PC and have a good internet
 connection? Let's hear those specs 💪!
--Yes Having Lenovo Ideapad i3, 11th gen,8gb ram,512ssd pc with good internet.
------------------------------------------------------------------------------------------------
Your stackoverflow, linkedin, personal site.
Anything you'd want us to see.
https://www.linkedin.com/in/alex-m-784913174
------------------------------------------------------------------------------------------------
What programming languages have you messed around with?
An opportunity to use my skills at [python,Java, flutter ], to perform and to be recognised
------------------------------------------------------------------------------------------------
- What sort of tooling is on your machine?
  - Programming languages, compilers, runtimes etc
  Java, Python, Flutter(dart), MySql. 
  - What OS do you run?
  Windows11.
  - What editor/IDE do you use?
  Intellij, VSCode, Android Studio.
  ------------------------------------------------------------------------------------------------
  Are you more into front-end or back-end? (If you're
  into web development).
  Back-end & Mobile App.
  ------------------------------------------------------------------------------------------------
  Are you interested in AI/ML, Systems Programming
  or anything outside your current domain.
  I'm very interested in AI/ML, Systems Programming, and a wide range of other topics outside my current domain
  ------------------------------------------------------------------------------------------------
  What are you learning now?
  spring boot.
------------------------------------------------------------------------------------------------


- Find the longest word in a string.
  - Given `The quick brown fox jumped over the lazy dog` is the input to your function, it should return `jumped`.

  Answer :
  function findLongestWord(str) {
    var longestWord = str.split(' ').sort(function(a, b) { return b.length - a.length; });
    console.log(longestWord[0]);
  }
  findLongestWord("The quick brown fox jumped over the lazy dog");
------------------------------------------------------------------------------------------------
- Repeat a string `n` times.
  - If `abc` and `3` are the arguments to your function, it shoudl return `abcabcabc`

  Answer :
  function repeatString(word,n){
  var output='';
  for(var i=1;i<=n;i++){output+=word;}
  console.log(output);
 }
 repeatString('abc',3);
------------------------------------------------------------------------------------------------
 - Remove duplicates in an array
  - If `[1, 20, 3, 1, 3, 3]` is the input to your
  function, it should return `[1, 20, 3]`

  Answer :
  function withoutDupicate(arr) {
  var uniqueNumbers = [];
  for (i = 0; i < arr.length; i++) {
    if (uniqueNumbers.indexOf(arr[i]) === -1) {
      uniqueNumbers.push(arr[i]);
    }
  }
  console.log(uniqueNumbers);
}
withoutDupicate([1, 20, 3, 1, 3, 3]);
------------------------------------------------------------------------------------------------
- Remove falsy values
  - If `[42, "everything", "", 2, false, "everything"]` is the input to your function, it should return `[42, "everything", 2, "everything"]`

    Answer :

function removingFalse(arr){
    let output = [];
for (let i = 0; i < arr.length; i++) {
  if (arr[i] !== false) {
    output.push(arr[i]);
  }
}
console.log(output);
}
removingFalse([42, "everything", "", 2, false, "everything"]);
------------------------------------------------------------------------------------------------

- Truncate a string
  - If `'Absolute victory'` and `3` are the inputs to
  your function, it should return `Abs...`

    Answer :

  function truncatedString(word, n) {

  console.log(word.slice(0, n) + '...');
}
truncatedString('Absolute victory', 3);

