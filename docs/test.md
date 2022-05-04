# Test

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.


=== "Android"

    ``` kotlin
    fun foo(a: Int = 0, b: String = "") { ... }
    ```

=== "iOS"

    ``` swift
    let individualScores = [75, 43, 103, 87, 12]
    var teamScore = 0
    for score in individualScores {
      if score > 50 {
          teamScore += 3
          } else {
            teamScore += 1
          }
        }
    print(teamScore)
    // Prints "11"
    ```

# Example

=== "Android"

    ``` c
    #include <stdio.h>

    int main(void) {
      printf("Hello world!\n");
      return 0;
    }
    ```

=== "iOS"

    ``` c++
    #include <iostream>

    int main(void) {
      std::cout << "Hello world!" << std::endl;
      return 0;
    }
    ```
