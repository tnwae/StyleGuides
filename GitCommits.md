# Git Commit Style Manual

Git is the version control system of choice for all Dreamacy projects.  Dreamacy operates a GitHub organization at <https://github.com/dreamacydd>.  Commit messages in Git must conform to the following guidelines, which are based on a Gist by Robert Painsi and on this guide at freeCodeCamp.

* Commit summary must be 72 characters or shorter; 50 characters is preferred.

* Commit summary must begin with one of the following genre descriptors that describes why a commit was made.  The emoji is preferred for brevity, but the spelled-out word may be used for parity with existing Git histories.
  * 🔧/`fix`: A problem in the code base was fixed.
  * 🧹/`chore`: Maintenance was performed on the code base, such as changing an option in a configuration file.
  * ✨/`feature`: A new feature was added to the application.
  * 📚/`docs`: A change was made pertaining to documentation.
  * 🧪/`testing`: A change was made pertaining to the test suite.
  * ⚒/`refactor`: A specific section of the code base has been refactored.
  * 💈/`style`: Changes were made pertaining to code style.
  * ⚖/`legal`/`policy`: A legal or policy change was made, such as updating the license, code of conduct, or other project rules.
* After the descriptor, a commit summary must be written in the imperative mood, with the notion being that if read as a complete sentence, one can state it as, “If applied, this commit will [perform the specified action].”
* If needed, the number of an issue ID in the issue tracker may be appended to a commit message in square brackets, e.g. [#1].
* If needed, an explanatory text may be added that explains the change(s) made.  Bullet points, written with a leading hyphen, are permissible with a two-space hanging indent.
* References to an issue tracker shall be placed at the bottom of the commit message (if closing an issue).
* Commit logs may potentially be furnished to customers; derogatory speech, swearing, and negative remarks about customers must be avoided.
