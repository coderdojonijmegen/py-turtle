---
title: "Python Turtle - Antwoorden"
date: 2020-08-24T21:41:04+02:00
draft: false
headercolor: "teal-background"
---

Let op: de volgende lijn ontbreekt aan de bovenkant van deze voorbeelduitwerkingen:

{{< highlight python >}}

    from turtle import *
    
{{< /highlight >}}

## Deel 1

### Opdracht 1-A

{{< highlight python >}}

    bgcolor('black')
    color('green')
    width(5)
    forward(100)
    right(90)
    forward(100)
    right(90)
    forward(100)
    right(90)
    forward(100)
    right(90)

{{< /highlight >}}
    
### Opdracht 1-B

{{< highlight python >}}

    bgcolor('black')
    color('yellow')
    width(3)
    left(90)
    
    forward(50)
    right(90)
    forward(200)
    right(90)
    forward(100)
    right(90)
    forward(200)
    right(90)
    forward(50)
    
    color('lightblue')
    width(1)
    right(45)
    forward(100)
    right(90)
    forward(100)
    right(90)
    forward(100)
    right(90)
    forward(100)

{{< /highlight >}}
    
### Opdracht 1-C

{{< highlight python >}}

    bgcolor('black')
    color('darkkhaki')
    width(5)
    forward(200)
    right(90)
    forward(100)
    right(90)
    forward(200)
    right(90)
    forward(100)
    
    color('red')
    width(2)
    right(45)
    forward(100)
    right(90)
    forward(100)
    
    color('darkkhaki')
    right(45)
    forward(100)

{{< /highlight >}}
    
## Deel 2

### Opdracht 2-A

Tip: 12 x 150 = 1800, en 1800 / 360 = 5. 
Omdat 1800 deelbaar is door 360, komen de hoeken precies goed uit voor een ster.

{{< highlight python >}}

    bgcolor('black')
    color('lightblue')
    width(3)
    
    for i in range(12):
        forward(100)
        right(150)

{{< /highlight >}}
        
### Opdracht 2-B

{{< highlight python >}}

    bgcolor('black')
    color('lightblue')
    width(3)
    for i in range(4):
        for j in range(3):
            forward(100)
            right(120)
        right(90)

{{< /highlight >}}
        
### Opdracht 2-C

Tip: In plaats van 360 en 1 kan je ook andere getallen kiezen.
Zorg dat deze keer elkaar 360 zijn.

{{< highlight python >}}

    bgcolor('black')
    color('lightblue')
    width(3)
    for i in range(360):
        forward(2)
        right(1)

{{< /highlight >}}
        
## Deel 3

### Opdracht 3-A

In deze voorbeelduitwerking staan 2 stempels.
Je kan er zelf nog een paar toevoegen als je wil!

{{< highlight python >}}

    bgcolor('black')
    color('yellow')
    width(5)
    fillcolor('lightyellow')
    begin_fill()
    setpos(0,200)
    setpos(200,200)
    setpos(200,0)
    setpos(0,0)
    end_fill()
    
    penup()

    setpos(50,50)
    shape('turtle')
    color('green')
    stempel1 = stamp()
    
    setpos(84,129)
    right(120)
    shape('turtle')
    color('blue')
    stempel2 = stamp()
    
{{< /highlight >}}
