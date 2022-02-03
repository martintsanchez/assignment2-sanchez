### Martin Sanchez

I am from Argentina, I am a senior at Northwest Missouri State University.<br>
I am part of the tennis team, and we start the season on February 18th.<br>

![Myself](https://user-images.githubusercontent.com/78869553/152177119-a8ceb3cd-1e87-4920-a6ad-497d73dc98ba.jpg)


-----

## Tables

There are many sports or activities that people should try, they all have different costs, but they are really good and needed for our heath.

|Sport   |     Where can be played?     |  Cost |
|:----------:|:-------------:|:------:|
| Basketball |  Park's court, garage, gym | $100 |
| Soccer |  Backyard, park, soccer field   |   $100 - $200 |
| Tennis | In a tennis club, or a park |    $200 - $350 |
| Volleyball | Park, pool, gym |    $150 - $320 |

-----

## Quotes

> Ever tried. Ever failed. No matter. Try again. Fail again. Fail better.
> _Samuel Beckett_ <br>
>Never bend your head. Always hold it high. Look the world straight in the eye.
> _Hellen Keller_

-----

### Code Fencing

Elementary Geometry
>the part of Euclidean geometry dealing with the simpler properties of straight lines, circles, planes, polyhedrons, the sphere, the cylinder, and the right circular cone.<br>
> <https://www.merriam-webster.com/dictionary/elementary%20geometry)>

~~~ 
struct point2d {
    ftype x, y;
    point2d() {}
    point2d(ftype x, ftype y): x(x), y(y) {}
    point2d& operator+=(const point2d &t) {
        x += t.x;
        y += t.y;
        return *this;
    }
    point2d& operator-=(const point2d &t) {
        x -= t.x;
        y -= t.y;
        return *this;
    }
    point2d& operator*=(ftype t) {
        x *= t;
        y *= t;
        return *this;
    }
    point2d& operator/=(ftype t) {
        x /= t;
        y /= t;
        return *this;
    }
    point2d operator+(const point2d &t) const {
        return point2d(*this) += t;
    }
    point2d operator-(const point2d &t) const {
        return point2d(*this) -= t;
    }
    point2d operator*(ftype t) const {
        return point2d(*this) *= t;
    }
    point2d operator/(ftype t) const {
        return point2d(*this) /= t;
    }
};
point2d operator*(ftype a, point2d b) {
    return b * a;
}
~~~
<https://cp-algorithms.com/geometry/basic-geometry.html>

