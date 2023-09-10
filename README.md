```js
import github from "github";

const githubProfile = () => {
  github.profile = {
    programmingLanguages: ["java", "javascript", "lua", "typescript", "sql"],
    skills: ["sass", "html", "css"],
    editors: ["neovim"],
    os: ["arch", "windows"],
  };

  try {
    github.contact = {
      discord: "igber",
      matrix: "@igberbn:matrix.org",
    };
  } catch (refuse) {
    console.error(refuse);
  }
};
```
