# Some equations
$$\left[\frac{n \times (n + 1)}{2}\right]^2$$
$$A \oplus B$$
![Operators in C](OperatorsinC.jpg "Opertors")


<details>
  <summary>Click me</summary>
  
  ### Heading
  1. Foo
  2. Bar
     * Baz
     * Qux

  ### Some Code
  ```js
  function logSomething(something) {
    console.log('Something', something);
  }
  ```
</details>


<details> 
    <summary> Problems </summary>

- <a href="https://www.codechef.com/problems/ALCARR" target="_blank">Click me</a>
- [Split and Maximize](https://www.codechef.com/problems/SPLITMAX)
- [String Game](https://www.codechef.com/problems/ABSTRING)
- [Splitting Balls](https://www.codechef.com/problems/SPBALL)

</details>

<details> 
  <summary> C++ </summary>

  ```c++
  #include <bits/stdc++.h>
  using namespace std;
  int main() {
    vector<int> arr(5) {10, 20, 30, 40, 50};
    vector<int> prefix(5);
    int sum = 0;
    for (int i = 0; i < n; i++) {
        sum += arr[i];
        prefix[i] = sum;
    }
  }
  ```

</details>

<details> 
  <summary> Java </summary>

  ```Java
  import java.util.*;
  class Prefix {
    public static void main (String args[]) {
        Scanner sc = new Scanner(System.in);
        int arr[5] = {10, 20, 30, 40, 50};
        int sum = 0;
        int []prefix = new int[5];
        for (int i = 0; i < n; i++) {
            sum = sum + arr[i];
            prefix[i] = sum;
        }
        sc.close();
    }
  }
  ```

</details>


<details> 
  <summary> Python </summary>

  ```python 
  nums = [10, 20, 30, 40, 50]
  sum = 0
  prefix = []
  for i in range(len(nums)):
    sum += nums[i]
    prefix[i] = sum
  ```

</details>


## Sorting Techniques
<details>
  <summary> Bubble Sort </summary>
  
  ![Bubble Sort Technique](bbs.gif)

</details>

<details>
  <summary> Video </summary>

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/e_04ZrNroTo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

</details>

<details>
  <summary> Video2 </summary>

  <video src="https://youtu.be/TJmTHuuYx3k" width=180/>

</details>


```plantuml
!define ICONURL https://raw.githubusercontent.com/tupadr3/plantuml-icon-font-sprites/v2.1.0
skinparam defaultTextAlignment center
!include ICONURL/common.puml
!include ICONURL/font-awesome-5/gitlab.puml
!include ICONURL/font-awesome-5/java.puml
!include ICONURL/font-awesome-5/rocket.puml
!include ICONURL/font-awesome/newspaper_o.puml
FA_NEWSPAPER_O(news,good news!,node) #White {
FA5_GITLAB(gitlab,GitLab.com,node) #White
FA5_JAVA(java,PlantUML,node) #White
FA5_ROCKET(rocket,Integrated,node) #White
}
gitlab ..> java
java ..> rocket
```

<!-- blank line -->
<figure class="video_container">
  <iframe src="https://www.youtube.com/embed/enMumwvLAug" frameborder="0" allowfullscreen="true"> </iframe>
</figure>
<!-- blank line -->