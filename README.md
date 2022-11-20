```js
export default class MyProfile {
  constructor() { }

  /**
   * @returns {string} Name
   */
  get name() {
    return "Robin";
  }

  /**
   * @returns {string} Gender
   */
  get gender() {
    return "male";
  }

  /**
   * @returns {Array<string>}
   */
  get skillset() {
    return [
      "C++", "C#", "Python", 
      "Kotlin", "Java"
      "React", "SQLite"
    ];
  }

  /**
   * @returns {Object}
   */
  get socials() {
    return {
      "discord": "KampfZomby#4574"
      "steam"  : "https://steamcommunity.com/id/pxnguintheoriginal/"
      "snapchat": "@kampfzomby"
    }
  }

  /**
   * @returns {string}
   */
  getMoreInfo() {
    return "https://kampfzomby.github.io/";
  }
}
```
