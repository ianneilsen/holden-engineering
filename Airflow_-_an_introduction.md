# Airflow - an introduction

How To Build A High-Performance Holden Six
Building the hot holden six
by snarlyjohn@gmail.com
Airflow - an introduction
Making power is largely about airflow. Of course there's more to it than that but
without adequate flow none of the other stuff really matters. It's just not possible to
give any more than a very brief overview in a page or two, but there are some very good
books on the subject if you'd like to learn more and I've included links to further reading
at the end of this page. But hopefully this will whet your appetite...
In the last section we looked at ways of maximising the quantity of air in the cylinder.
But specifically, what's important is the
mass
of the cylinder charge. And that mass is
in proportion to the temperature of the charge - there's more air in a 33cu.in. charge when it's at
say 20 degrees than at 50 degrees. Cooling the intake charge is probably the quickest and easiest
ways of improving the VE that you'll find. With most vehicles it's possible to arrange the intake
to pick up air from a point that reduces the temperature and increases the pressure when compared to
a standard under-bonnet setup.
What about vapourising fuel in the intake tract as a way of decreasing charge temperatures? It's
currently fashionable in some circles to shift the injection nozzles upstream for just this purpose.
With oxygen-carrying fuels like methanol (which incidentally also has a high latent heat of vapourisation) it's pretty
easy to show that early vapourisation can show a net benefit. But with fuels like petrol it isn't
so clear cut. When a liquid like petrol vapourises as well as absorbing a lot of heat it also increases
its volume by a huge amount. So on one hand we have a decrease in temperature helping to increase charge
density, but on the other the massive increase in volume of fuel displaces some of the working fluid (air)
from the charge. This may help explain why so many engines (especially those that are flow limited) 
are so insensitive to petrol atomisation in the
intake - and in fact flow limited engines seem to make more power when the fuel is fed as a solid stream.
With petrol at least, it's probably not worth the effort to encourage fuel vapourisation in the inlet.
Let's have a look at air. Like anything else with mass it's subject to Newton's laws of motion.
In simple terms, when it's stationary it wants to stay that way and it takes work to get it moving.
When it's moving it takes effort to change its speed or direction. And a moving volume of air contains
some amount of kinetic energy, the energy that was invested in it to get it moving in the first place.
Recovery of at least some of this energy is an important part of power production. But while air has mass
it is also compressible and elastic. As a result of this it's usual for all the particles of air and fuel
in a port or runner to be travelling at widely varying speeds. They might even be travelling in different
directions. If you could see the air it would look more
like a "Slinky" with waves bouncing back and forth than a column of incompressible liquid. Remember this; it's
important and something that we'll touch on again shortly.
Air has mass, but it doesn't behave like a solid incompressible column at all. The effects of inertia are largely negligible.
One way to visualise the air within an engine duct is to imagine it as being something like a Slinky toy.
Pretty much everything we do to maximise flow has the same aim - we want the airflow to be smooth and controlled
and within certain velocity and turbulence limits. Having said that pretty much every part of an engines ducting
will carry flow that is basically turbulent; we just need to limit that turbulence to a point where it doesn't
disrupt the flow too severely. In practice we might use a bellmouth on the carb intake to accelerate the air smoothly
into the throat. In the carb we need to accelerate the air further so that we have a localised low pressure zone into which
the fuel can be pushed by atmospheric pressure. Once the fuel is added we then need to allow the air to slow down
again, hopefully in a way that lets us recover energy. Now this re-expansion phase is important to understand, not
just in terms of carburation but throughout the engine as a whole. So we'll take a closer look at this process now.
I think everyone reading this will be familiar with the shape of a venturi. Typically it will have a large inlet and
outlet diameter with a smaller throat at some point in the middle, where the velocity is high and the pressure low.
The inlet transition is generally a simple radius shape, and is relatively short - usually a fraction of the length
of the outlet or downstream transition. There is a good reason for this; air can be accelerated into a constricted
area relatively easily over a short distance without much loss of efficiency or energy. Expansion is a different
story altogether though; if we try to make it happen too quickly the flow will separate from the walls and become
turbulent and this in turn leads to a dramatic reduction in flow. This is a really important concept to understand;
a very large proportion of the productive port work will be related to minimising flow separation. Novice builders
tend to put too much effort into easing the entry side of restrictions and not enough effort into the downstream
side. In simple terms the upstream approach to any high velocity zone isn't so important, the downstream side critically
so.
These "flow expansion zones" are everywhere throughout the engine flow path. Some examples: the transition from
throttle body to plenum with an injected engine, or carb to plenum with a carburated engine. The port throat to
turn is another area, the runner to head port transition of a 9 port engine another, the valve seat to cylinder yet another.
On the exhaust side the collector is a good example.
As mentioned previously novice builders often seem to sweat over things like bellmouths and port matching when the
real gains are to be made at the opposite end. Keep in mind though that anywhere there is wet flow you may be working
with conflicting requirements. For example the turbulence created by the rapid expansion under a carb may reduce bulk
flow but it may also help with fuel mixing, and which is the dominant effect may only be determined by experimentation.
This would explain why "Super Sucker" style carb spacers work very well on some engines but not others.
So we've established that while air doesn't like to be sped up, it likes being slowed down even less. In practical terms
any surface that diverges from the flow path at an angle sharper than 10 to 15 degrees will cause flow separation. This
would include any port or runner walls as well as the faces of the valve and seat and any approach and departure angles.
As far as wall finish goes I think it's pretty well recognized now that a highly polished is not what we want. I've found that
for good flow a plain old carbide finish is as good as any, though most professional porters will finish with a coarse sanding
roll for the sake of appearance. This doesn't seem to hurt flow, but if you have an old-style head with polished walls it will
definitely hurt performance from both a flow and fuel suspension perspective.
We could summarise porting (whether it's head porting or manifolds etc.) in just a few lines - porting in essence is simply
is an attempt to do one of the following:
To keep the air velocity within certain limits (in order to limit turbulence and the resulting flow losses)
To keep turbulence within limits
To keep the air attached to the surrounding surfaces and prevent them from becoming detached and turbulent.
You could further distill that summary down to just five words -
we port to limit turbulence.
In the last section we touched on the Kadenacy Effect, but we'll now cover it in a little more detail. It was originally
conceived many years ago to help explain the behaviour in two-stroke exhaust systems. In essence it describes a "slug of gas"
or a "gaseous piston" that is created in the pipe when the exhaust port or valve is opened and shot down the pipe. The theory states
that the momentum of the slug pulls the remaining gas out behind it. It's a good theory in that it neatly explains the period of
low pressure found in most systems and is widely quoted in many textbooks and magazine articles on engine tuning. The only problems
with it are the facts that it's pure horseshit and was comprehensively disproved back in the 1940's. Despite this the Kadenacy Effect
is still commonly quoted as if it was true and many other mass-based effect are widely believed even though they have little basis
in fact. People still talk about tuning using the momentum of a column of gas (the water hammer effect) among other things but
again this is mostly fiction. In recent years it has become quite easy to fit an engine with pressure transducers in a variety
of places and see in real time exactly what is happening in a running engine. And it turns out that all these various pressure
surges have next to nothing to do with the mass or momentum of the charge and everything to do with finite pressure waves bouncing
around within the system.
If there is one area where the "charge-momentum" effect is most widely misused it would have to be that period between BDC on the
intake stroke and the intake closing point. It's often claimed that the cylinder is mostly full at BDC and that the momentum of
the high-velocity air flowing through the intake tract keeps it flowing in for a time even though the piston has reversed and is
starting to rise again. Real time testing show the reality to be completely different. When the piston reaches BDC on the intake stroke
- and this is particularly true with "wheezers" like our Holden sixes - the cylinder pressure is still well under atmospheric. The
air does continue to flow in, but it's because of plain old pressure differential, not momentum. Eventually of course, as the piston
rises and the air continues to flow in the pressures reach equalibrium and this is where we want to close the valve. Without assistance
from finite pressure waves it's very very difficult to achieve a 100% fill, let alone exceed it.
By modern standards the Holden six is grossly underported, and it's interesting to compare it to a more modern design to see what's possible
with better port flow and wave action. A good example would be the Ford "Coyote" engine - it'd be very close to being state of the art in high-volume production engines.
The Coyote is a four-valve engine with 2:1 finger rockers. It's not a racing engine but a mildly tuned, quiet and civilised passenger car engine. Stock standard it achieves a VE of over 110%, a figure that was found only amongst high-level racing engines not that long ago. Tuned length intake runners are arranged in such a way to enable VEs of over 100% over a wide rpm range. To put that in perspective an
equivalent 202 would make around 275hp while pulling strongly from idle. Now, a 275hp 202 mightn't sound all that remarkable but consider this: the
Coyote does all this with only about 250 degrees of intake duration,
seat-to-seat
! It's not highly tuned by any
stretch of the imagination.
I mention the Coyote not to rubbish the little Holden but to illustrate just how important it is to maximise the area under the flow curve
and show what is achievable with enough flow, even with a very short cam. Maximising flow should be our first priority.
Further Reading
-
Engine Airflow by Harold Bettes
is a good place to start learning about airflow. There is a surprising amount of
good information here, and it's written in an easy to follow way.
How to Port & Flow Test Cylinder Heads by David Vizard
is a good practical guide.
Previous page: Horsepower and where to find it
Table of Contents
Next page: Planning Your Engine
Building the Hot Holden Six
by
snarlyjohn@gmail.com
is licensed under a
Creative
Commons License
and was written using
gedit
under
Linux.
Copyright © 2008. Design
based on a free template from
NodeThirtyThree
Design
.