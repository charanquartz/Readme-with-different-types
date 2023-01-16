```java
// Java program for simple calculator

import java.io.*;
import java.lang.*;
import java.lang.Math;
import java.util.Scanner;
public class BasicCalculator {

	public static void main(String[] args)
	{
		// stores two numbers
		double num1, num2;

		// Take input from the user
		Scanner sc = new Scanner(System.in);

		System.out.println("Enter the numbers");

		// take the inputs
		num1 = sc.nextDouble();

		num2 = sc.nextDouble();

		System.out.println("Enter the operator (+,-,*,/)");

		char op = sc.next().charAt(0);

		double o = 0;

		switch (op) {

		// case to add two numbers
		case '+':

			o = num1 + num2;

			break;

		// case to subtract two numbers
		case '-':

			o = num1 - num2;

			break;

		// case to multiply two numbers
		case '*':

			o = num1 * num2;

			break;

		// case to divide two numbers
		case '/':

			o = num1 / num2;

			break;

		default:

			System.out.println("You enter wrong input");

			break;
		}

		System.out.println("The final result:");

		System.out.println();

		// print the final result
		System.out.println(num1 + " " + op + " " + num2
						+ " = " + o);
	}
}
```

Here is a simple flow chart:

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```
```geojson
{
  "type": "FeatureCollection",
  "features": [
    {
      "type": "Feature",
      "id": 1,
      "properties": {
        "ID": 0
      },
      "geometry": {
        "type": "Polygon",
        "coordinates": [
          [
              [-90,35],
              [-90,30],
              [-85,30],
              [-85,35],
              [-90,35]
          ]
        ]
      }
    }
  ]
}
```

```topojson
{
  "type": "Topology",
  "transform": {
    "scale": [0.0005000500050005, 0.00010001000100010001],
    "translate": [100, 0]
  },
  "objects": {
    "example": {
      "type": "GeometryCollection",
      "geometries": [
        {
          "type": "Point",
          "properties": {"prop0": "value0"},
          "coordinates": [4000, 5000]
        },
        {
          "type": "LineString",
          "properties": {"prop0": "value0", "prop1": 0},
          "arcs": [0]
        },
        {
          "type": "Polygon",
          "properties": {"prop0": "value0",
            "prop1": {"this": "that"}
          },
          "arcs": [[1]]
        }
      ]
    }
  },
  "arcs": [[[4000, 0], [1999, 9999], [2000, -9999], [2000, 9999]],[[0, 0], [0, 9999], [2000, 0], [0, -9999], [-2000, 0]]]
}
```

```stl
solid cube_corner
  facet normal 0.0 -1.0 0.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 1.0 0.0 0.0
      vertex 0.0 0.0 1.0
    endloop
  endfacet
  facet normal 0.0 0.0 -1.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 0.0 1.0 0.0
      vertex 1.0 0.0 0.0
    endloop
  endfacet
  facet normal -1.0 0.0 0.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 0.0 0.0 1.0
      vertex 0.0 1.0 0.0
    endloop
  endfacet
  facet normal 0.577 0.577 0.577
    outer loop
      vertex 1.0 0.0 0.0
      vertex 0.0 1.0 0.0
      vertex 0.0 0.0 1.0
    endloop
  endfacet
endsolid
```

```classDiagram
classDiagram
Class01 <|-- AveryLongClass : Cool
Class03 *-- Class04
Class05 o-- Class06
Class07 .. Class08
Class09 --> C2 : Where am i?
Class09 --* C3
Class09 --|> Class07
Class07 : equals()
Class07 : Object[] elementData
Class01 : size()
Class01 : int chimp
Class01 : int gorilla
Class08 <--> C2: Cool label
```

This sentence uses `$` delimiters to show math inline:  $\sqrt{3x-1}+(1+x)^2$


**The Cauchy-Schwarz Inequality**

$$\left( \sum_{k=1}^n a_k b_k \right)^2 \leq \left( \sum_{k=1}^n a_k^2 \right) \left( \sum_{k=1}^n b_k^2 \right)$$


**Here is some math!**

```math
\sqrt{3}
```


This expression uses `\$` to display a dollar sign: $\sqrt{\$4}$




\begin{equation}
  x = a_0 + \cfrac{1}{a_1 
          + \cfrac{1}{a_2 
          + \cfrac{1}{a_3 + \cfrac{1}{a_4} } } }
\end{equation}



To split <span>$</span>100 in half, we calculate $100/2$



<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://user-images.githubusercontent.com/25423296/163456776-7f95b81a-f1ed-45f7-b7ab-8fa810d529fa.png">
  <source media="(prefers-color-scheme: light)" srcset="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
  <img alt="Shows an illustrated sun in light mode and a moon with stars in dark mode." src="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
</picture>






## About me

Hi, I'm Mona. You might recognize me as GitHub's mascot.












| Rank | THING-TO-RANK |
|-----:|---------------|
|     1|               |
|     2|               |
|     3|               |














## About me

Hi, I'm Mona. You might recognize me as GitHub's mascot.

| Rank | Languages |
|-----:|-----------|
|     1| Javascript|
|     2| Python    |
|     3| SQL       |


<details>
<summary>My top THINGS-TO-RANK</summary>

YOUR TABLE

</details>




















<details>
<summary>My top languages</summary>

| Rank | Languages |
|-----:|-----------|
|     1| Javascript|
|     2| Python    |
|     3| SQL       |
  
</details>



















---
> If we pull together and commit ourselves, then we can push through anything.

— Mona the Octocat






## About me

<!-- TO DO: add more details about me later -->







... when `x<y` we have ...


... when `x < y` we have ...
... when `x &lt; y` we have ...


\\begin{array}{cc}
  a & b \\\\
  c & c
\\end{array}




\(
   \def\RR{{\bf R}}
   \def\bold#1{{\bf #1}}
\)




window.MathJax = {
  tex: {
    macros: {
      RR: "{\\bf R}",
      bold: ["{\\bf #1}", 1]
    }
  }
};






//

``` { .lang #example style="color: #333; background: #f8f8f8;" }
A code block with inline styles. Fancy!
```
//