<a name="readme-top"></a>
<hr>
<br />
<div align="center">
  <a href="https://github.com/BelalHassan7/Truncatable_Primes">
  </a>
<h3 align="center">Truncatable_Primes</h3>
  <p align="center">
    <br />
    <a href="https://github.com/BelalHassan7/Truncatable_Primes"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/BelalHassan7/Truncatable_Primes">View Demo</a>
    ·
    <a href="https://github.com/BelalHassan7/Truncatable_Primes/issues">Report Bug</a>
    ·
    <a href="https://github.com/BelalHassan7/Truncatable_Primes/issues">Request Feature</a>
  </p>
</div>
<hr>


<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#About-The-Project">About The Project</a>
      <ul>
        <li><a href="#Built-With">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#Functions">Functions</a>
    </li>
    <li><a href="#Contact">Contact</a></li>
  </ol>
</details>

## About The Project

This library proviedes the user with functions for finding truncatable primes: 

1. Left-truncatable primes
2. right-truncatable priems
3. left-and-right-truncatable primes
4. primes that are both left and right truncatable primes. 

The last two types of primes are not the same: left-and-right truncatable primes are primes that stay primes by removing their left and right digits, but the last one is a left-truncatable prime and a right-truncatable prime at the same time. 

Note: Functions for left-and-right truncatable primes are still under construction.

### Built With

* [![visual][visual.js]][visual-url]
<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Functions


* `bool isPrime(int num)` checks if a num is prime.

* `bool isRTP(int num)` checks if a num is a right-truncatable prime (RTP).

* `bool isLTP(int num)` checks if a num is a left-truncatable prime (LTP).

* `bool isTP(int num)` checks if a num is a RTP and a LTP at the same time (TP).

* `void RTPs(int n)` outputs all n-digit RTPs. 

* `void LTPs(int n)` outputs all n-digit LTPs. 

* `void TPs(int n)` outputs all n-digit TPs. 
<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Contact

Belal - belal.34327@gmail.com

Project Link: [https://github.com/BelalHassan7/Truncatable_Primes](https://github.com/BelalHassan7/Truncatable_Primes.git)
<p align="right">(<a href="#readme-top">back to top</a>)</p>

[visual.js]: https://img.shields.io/badge/Visual-Studio?style=for-the-badge&logo=visual%20studio&logoColor=800080&labelColor=000000&color=000000
[visual-url]: https://visualstudio.microsoft.com
