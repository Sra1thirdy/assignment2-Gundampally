# assignment2-Gundampally
# Sravanthi Gundampally
###### Nizamabad

Nizamabad, also called Indur, city, northwestern Telangana state, southern India. The city is located on a level upland plain of the Telangana Plateau, north-northwest of Hyderabad.Nizamabad lies on a rail line to Hyderabad, and it is connected to Hyderabad and to Adilabad to the north by a national highway. Historical points of interest include a temple (that now houses a water-supply tank) and the fort of Indur. The city is also the site of **Nizam College** (established 1887), which is affiliated with Osmania University in Hyderabad.

---

### Route map

1. Go to MCI airport, kansas city
2. Board into a flight to RGIA airport, India
3. Book a ola/uber and go to busstop then get into a nizamabad bus.
   1. Rent a car
   2. visit the nearest agriculture lands and enjoy the scenary
* Biscuits
* umbrella
* DSLR   

[AboutMeLink](AboutMe.md)

---

### Recommended food

Below table shows the food items and their locations and price of them.

|    Food Items   |     Location     |   Amount    |
|   -----------   |    ----------    |  --------   |
| samosa          |   nizamabad      |    50       |
|pani puri        |   Nizamabad      |    20       |
|wada pav         |   Delhi          |    40       |
|ice cream        |   Bengalore      |    550      |

---

### quotes

You cannot believe in God until you believe in yourself -          *swamy vivekananda*      
All our dreams can come true, if we have the courage to pursue them – *Walt Disney*

---

## code fencing

### Algebra

> Algebra is a branch of mathematics dealing with symbols and the rules for manipulating those symbols. In elementary algebra, those symbols (today written as Latin and Greek letters) represent quantities without fixed values, known as variables. Just as sentences describe relationships between specific words, in algebra, equations describe relationships between variables

> (https://www.livescience.com/50258-algebra.html)

---

pair<int, int> fib (int n) {
    if (n == 0)
        return {0, 1};

    auto p = fib(n >> 1);
    int c = p.first * (2 * p.second - p.first);
    int d = p.first * p.first + p.second * p.second;
    if (n & 1)
        return {d, c + d};
    else
        return {c, d};
}

---
Link : (<https://cp-algorithms.com/algebra/fibonacci-numbers.html>)
