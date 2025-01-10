# Machine Learning Online Resources: Fundamentals

<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a name="readme-top"></a>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#math">Math</a>
      <ul>
        <ul>
          <a href="#linear-algebra">Linear Algebra</a>
          <li><a href="#linear-algebra">Linear Algebra</a></li>  
        </ul>
        <li><a href="#probability">Probability</a></li>
        <li><a href="#statistics">Statistics</a></li>
        <li><a href="#information-theory">Information Theory</a></li>
        <li><a href="#optimization">Optimization</a></li>
      </ul>
    </li>
    <li>
      <a href="#machine-learning">Machine Learning</a>
      <ul>
        <li><a href="#trees">Trees</a></li>
      </ul>
    </li>
    <li>
      <a href="#deep-learning">Deep Learning</a>
      <ul>
        <li><a href="#transformers">Transformers</a></li>
      </ul>
    </li>
  </ol>
</details>

<!-- Math -->
## Math

<!-- Linear Algebra -->
### Linear Algebra

#### Linear Equations
| Source  | Notes |  Featured Images |
| :------------ |:---------------:|:---------------:|
| [Don’t invert that matrix](https://www.johndcook.com/blog/2010/01/19/dont-invert-that-matrix/) <br> [COS 302: Matrix Inversion](https://www.youtube.com/watch?v=5aPP9tGgC-s) | Inverting a matrix is expensive and not numerically stable. So, when solving linear equations, we don't invert the matrix. Instead, we solve the linear equation using LU decomposition, iterative solvers, or optimization methods. | ![alt text](https://github.com/sianjin/Machine-Learning-Free-Resource-Fundamentals/blob/main/images/linear-algebra/inverse_matrix_unstable_COS302%20.png) ![alt text](https://github.com/sianjin/Machine-Learning-Free-Resource-Fundamentals/blob/main/images/linear-algebra/solve_linear_equations_COS302%20.png) |

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- Probability -->
### Probability


<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- Statistics -->
### Statistics


<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- Information Theory -->
### Information Theory


<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- Optimization -->
###  Optimization

<p align="right">(<a href="#readme-top">back to top</a>)</p>







<!-- Machine Learning -->
## Machine Learning

<!-- Trees -->
### Trees

<p align="right">(<a href="#readme-top">back to top</a>)</p>







<!-- Deep Learning -->
## Deep Learning

<!-- Transformers -->
### Transformers

#### Attention
This section illustrates why and how to combine attention mechanism with a Sequence-to-Sequence network.

| Source  | Notes | 
| :------------ |:---------------:|
| [Attention for Neural Networks, Clearly Explained!!!](https://www.youtube.com/watch?v=PSs6nxngL6k)     |  Great motivation of attention mechanism: which word needs to come first. |
[Visualizing A Neural Machine Translation Model (Mechanics of Seq2seq Models With Attention)](https://jalammar.github.io/visualizing-neural-machine-translation-mechanics-of-seq2seq-models-with-attention/)      | Overview of the difference between Sequence-to-Sequence and Sequence-to-Sequence with attention.  |

<p align="right">(<a href="#readme-top">back to top</a>)</p>

#### Basic Transformers Network Achitecture
This section illustrates the network architecture from the paper "[Attention Is All You Need](https://arxiv.org/abs/1706.03762)".
| Source  | Notes | Featured Images |
| :------------ |:---------------:|:---------------:|
| [The Illustrated Transformer (initial part)](https://jalammar.github.io/illustrated-transformer/)     | Great break down of encoder-decoder flow from top to bottom.  | ![alt text](https://github.com/sianjin/Machine-Learning-Free-Resource-Fundamentals/blob/main/images/transformers/encoder_decoder_overview_1_jalammar.png) ![alt text](https://github.com/sianjin/Machine-Learning-Free-Resource-Fundamentals/blob/main/images/transformers/encoder_decoder_overview_2_jalammar.png) |
| [Transformer Neural Networks, ChatGPT's foundation, Clearly Explained!!! (last part)](https://www.youtube.com/watch?v=zxQyTK8quyY&t=1s)     | Great illustration of encoder-decoder flow.  |![alt text](https://github.com/sianjin/Machine-Learning-Free-Resource-Fundamentals/blob/main/images/transformers/encoder_decoder_overview_SQ.png)|
| [The Illustrated Transformer (middle part)](https://jalammar.github.io/illustrated-transformer/)     |  Great answer of what Q, K, V are and their matrix operations. <br> The multi-head attention machanism is also very clear. |![alt text](https://github.com/sianjin/Machine-Learning-Free-Resource-Fundamentals/blob/main/images/transformers/qkv_1_jalammar.png) ![alt text](https://github.com/sianjin/Machine-Learning-Free-Resource-Fundamentals/blob/main/images/transformers/qkv_2_jalammar.png) ![alt text](https://github.com/sianjin/Machine-Learning-Free-Resource-Fundamentals/blob/main/images/transformers/qkv_3_jalammar.png)|
| [Transformer Neural Networks, ChatGPT's foundation, Clearly Explained!!! (middle part)](https://www.youtube.com/watch?v=zxQyTK8quyY&t=1s)     | Great illustration of positional encoding and encoder-decoder flow.  | ![alt text](https://github.com/sianjin/Machine-Learning-Free-Resource-Fundamentals/blob/main/images/transformers/positional_encoding_SQ.png)|
<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/sian-jin-0461a4188/
[product-screenshot]: images/screenshot.png
[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[Vue-url]: https://vuejs.org/
[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
[Svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[Svelte-url]: https://svelte.dev/
[Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[Laravel-url]: https://laravel.com
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com 
