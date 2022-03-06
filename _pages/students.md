---
layout: page
permalink: /students/
title: Students
description:  
years: [UIC, PRIMES-MIT]
nav: false
heading: Students
---

<div class="publications">

In the last decade I have mentored several students at different levels. Below is a list of my former and current students.  To find more information about my broader "academic family" visit my <a href="https://www.mathgenealogy.org/id.php?id=171532">genealogy</a> entry. 
 
 <br>
 <hr>
<span style="font-size:15px">

<h2>Current</h2>
 
 {%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f current -q @*[year={{y}}]* %}
{% endfor %}

  <br>

 <hr>
<span style="font-size:15px">

<h2>Former</h2>

In reverse chronological order

<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f past -q @*[year={{y}}]* %}
{% endfor %}

 

@article{qingyun,
    title = {<a href="https://phys.uic.edu/profiles/wang-qingyun/"> Qingyun Wang</a>},
    color = {lightgrey},
    year = {UIC},
    author = {2020-},
    journal = {Current PhD student at UIC.},
    img = {/assets/img/qingyun.png}
    }

@article{prolay,
    title = {<a href="https://phys.uic.edu/profiles/chanda-prolay/"> Prolay Chanda</a>},
    color = {lightgrey},
    year = {UIC},
    author = {2017-},
    journal = {Current PhD student at UIC.},
    img = {/assets/img/prolay.png}
    }

@article{saleh,
    title = {<a href="https://uic.academia.edu/SalehHamdan"> Saleh Hamdan</a>},
    color = {lightgrey},
    year = {UIC},
    author = {2016-18},
    journal = {Dark Matter Freeze-out in a Matter Dominated Universe <br> PhD defended July 2018 <br> Current Postdoctoral Research Fellow at Medical College of Wisconsin.},
    img = {/assets/img/saleh.png}
    }

@article{alex,
    title = {<a href="https://math.mit.edu/research/highschool/primes/conference/index.php"> Alex Liang</a>},
    color = {lightgrey},
    year = {PRIMES-MIT},
    author = {2021-22},
    journal = {Predicting Pandemics with Stock Market Indicators <br> MIT Primes Student 2021 <br> Accepted for UG at MIT.},
    img = {/assets/img/alex.png}
    }


@article{yunseo,
    title = {<a href="https://math.mit.edu/research/highschool/primes/conference/conf-2020.php"> Yunseo Choi</a>},
    color = {lightgrey},
    year = {PRIMES-MIT},
    author = {2020-21},
    journal = {Racial Impact on Infections and Deaths Due to COVID-19 in New York City <br> MIT Primes Student 2020 <br> 2020 Yau Science Award USA medalist (Bronze in Physics) <br> Current UG at Harvard.},
    img = {/assets/img/yunseo.png}
    }


@article{benjamin,
    title = {<a href="https://math.mit.edu/research/highschool/primes/conference/conf-2019.php"> Benjamin Kang</a>},
    color = {lightgrey},
    year = {PRIMES-MIT},
    author = {2019-20},
    journal = {All-Pay Auctions with Different Forfeit Functions <br> MIT Primes Student 2019 <br> 2020 Regeneron STS scholar <br> 2019 Yau Science Award USA finalist (Gold in Economic and Financial Modeling) <br> 2019 Yau Science Award Global medalist (Bronze in Economic and Financial Modeling) <br> Current UG at MIT.},
    img = {/assets/img/benjamin.png}
    }

@article{carlos,
    title = {<a href=""> Carlos Maldonado</a>},
    color = {lightgrey},
    year = {Chile},
    author = {2018-19},
    journal = {Visiting PhD student from Universidad de Santiago de Chile.},
    img = {/assets/img/carlos.png}
    }

@article{vincent,
    title = {<a href="https://math.mit.edu/research/highschool/primes/conference/conf-2018.php"> Vincent Huang</a>},
    color = {lightgrey},
    year = {PRIMES-MIT},
    author = {2018-19},
    journal = {Mathematical and Algorithmic Models of Refugee Crises <br> MIT PRIMES Student 2018 <br> 9th in Regeneron STS 2019 <br> Current UG at MIT.},
    img = {/assets/img/vincent.png}
    }

@article{kyle,
    title = {<a href="https://math.mit.edu/research/highschool/primes/conference/conf-2017.php"> Kyle Gatesman</a>},
    color = {lightgrey},
    year = {PRIMES-MIT},
    author = {2017-18},
    journal = {An Algorithmic and Computational Approach to Optimizing Gerrymandering <br> MIT PRIMES Student 2017 <br> Siemens Competition Semi-Finalist <br> Current UG at Johns Hopkins.},
    img = {/assets/img/kyle.png}
    }

