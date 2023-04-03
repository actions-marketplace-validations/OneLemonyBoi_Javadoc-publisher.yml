# SOR Deploy/Publish JavaDoc

Automatically generate Javadoc from your Java project and publish it to GitHub Page. Modified by Team 6059.

## Requirements
- Your project need to use **Maven** or **Gradle**.
<details>
<summary>
<h2>Inputs</h2>
</summary>

| input             | description                                                | default |
|-------------------|------------------------------------------------------------|------------------|
| java-version      | java version inside your project                           | 17               |
| GITHUB_TOKEN      | The GitHub token the GitHub repository                     |                  |
| javadoc-branch    | Branch where the javadoc is hosted                         | javadoc          |
| target-folder     | Directory where the javadoc contents should be stored      | .                |
| java-distribution | Java distribution inside your project                      | adopt            |
| project           | Maven or Gradle project                                    | maven            |
| custom-command    | Custom command to generate the javadoc                     | ""               |
| subdirectories    | Custom subdirectories to upload from                       |                  |
| without-deploy    | Enable or disable deploy of the javadoc to the GitHub Page | false            |
| without-checkout  | Enable or disable the checkout                             | false            |
</details>

## License
The Dockerfile and associated scripts and documentation in this project are released under the [Apache 2.0 License](https://github.com/MathieuSoysal/publish-javadoc/blob/main/LICENSE).
