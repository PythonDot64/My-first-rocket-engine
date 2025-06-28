# first rocket engine

## Preamble (you can skip this part)

This is my first ever rocket engine so I'll admit it is not that great, but it works so I am not complaining, and even though it doesn't look great, it is still hard to make (for reference, this thing took me THREEE MONTHS TO MAKE! YES _**THIS**_ TINY LITTLE THING TOOK ME THREE MONTHS).

I made this engine using the [NASA CEA](https://cearun.grc.nasa.gov/) and [this website](https://risacher.org/rocket/). I used NASA CEA mainly to get the estimated performance of the rocket engine, and the other webiste is to calculate the geometry of the rocket engine

## nozzle

This engine nozzle is a convergent nozzle design, since it was the easiest for me to design and build. The convergent nozzle is not very efficient performance wise, since the best it can do is make the exhaust sonic (the speed of sound). This is because this nozzle works by compressing the exhaust of the rocket engine so that it goes fast (according to physics), but this has a fatal flaw: the exhaust at the fastest can only go sonic. The reason for this is because, according to fluid dynamics (and hot rocket exhaust counts as a fluid), fluid at sonic speed and higher is no longer compressible so the exhaust can't be faster.

This nozzle is made of 316L stainless steel (and not rubber although it does look like it). This decision was made because 316L can be 3D printed, therefore I can rapidly iterate through designs, and it can withstand high temperatures.

More about rocket engines [here](https://www.youtube.com/watch?v=gz8L1i0ODeA)

## injector

This injector is of a showerhead design, since it was also the easiest for me to design and build. This type of injector is not very efficient performance wise. This is because an injector's job is to inject fuel and oxidizer while mixing and atomizing (to turn liquid into tiny droplets) them with tiny holes, and the showerhead design is not good at that since the holes are aimed straight up so it doesn't mix at all and how well it can atomize mostly depends on how small the holes are.

## future improvements

This rocket engine is not very good performance wise and there are several ways to impove it:

1. Use the correct measurement for the engine. For example, I modeled the engine in mm but I calculated the geometry in inches, and I didn't convert it into mm.
2. Use a more efficient nozzle design. Convergent engines are not efficient, and something like a conical engine would be better.
3. Use a more efficient injector design. Although showerheads are easy to make. They are not ideal if you are looking for performance.
4. Use better equipment. Although Butane and air as fuel and oxidizer is not bad, but it just is not the best choice if you want thrust. A better choice would be liquid hydrogen as fuel and liquid oxygen as oxidizer.

## how to use (a.k.a view, 3D print, etc)

1. Open powershell
2. Download [git](https://git-scm.com/downloads) if you haven't already. Ensure it is downloaded with the command `git --version` in powershell, and you should see something similar to this: `git version 2.45.2.windows.1`
3. Download a CAD (Computer Aided Design) program if you haven't already. For people that is welling to pay, I recommend Fusion 360 or Solidworks. For those who doesn't want to pay, you can use the free version of Fusion 360 or Onshape. It can be anything but it has to be able to open a .step or a .stp file
4. Type in the powershell `cd Downloads; git clone https://github.com/PythonDot64/first-rocket-engine.git`
5. Open your CAD software of choice and open the files in the CAD software
