---
slug: "orbit-solution-2026-k1"
title: "Orbit solution — no ballistic fit, a constant deceleration, and a mass"
date: 2026-04-25
document_code: "ORB-2026-K1"
facility: "Minor body dynamics working group"
author: "Dynamics working group, 11 contributing observatories"
distribution: "PUBLIC"
---

===========================================================================
                  MINOR BODY DYNAMICS WORKING GROUP
                     ORBIT SOLUTION  2026-K1
===========================================================================

OBJECT              CVIS-DR7-04471
ARC                 2026-03-28 to 2026-04-25  (28 days, 611 observations)
OBSERVATORIES       11
ISSUED              2026-04-25  22:15 UT

---------------------------------------------------------------------------

RESULT

No bound orbit fits the astrometry. No unperturbed hyperbolic orbit fits
it either.

    heliocentric distance, 2026-03-28       30.07 AU
    heliocentric distance, 2026-04-25       22.42 AU
    radial velocity, 2026-03-28            559.3 +/- 2.1 km/s
    radial velocity, 2026-04-25            387.1 +/- 2.4 km/s
    solar escape velocity at 30.07 AU        7.68 km/s
    ratio at discovery                       72.8

    specific orbital energy                 +1.564e11 J/kg   (UNBOUND)

The largest hyperbolic excess velocity measured for a confirmed
interstellar object is 58 km/s (3I/ATLAS, 2025). This object entered our
arc moving 9.6 times faster than that.

It is also, plainly, slowing down. Those two velocities are six hundred
and seventy-two hours apart.

---------------------------------------------------------------------------

THE RESIDUALS, WHICH ARE THE ACTUAL RESULT

The best six-element ballistic solution leaves residuals of

    28 Mar   14"      4 Apr   1.0"      11 Apr   0.2"
    18 Apr  1.4"     25 Apr    25"

against a per-observation astrometric uncertainty of 0.06". The last of
those is four hundred times our noise, in a fit with six free parameters
and 611 observations.

They do not grow monotonically, and the shape of them is the argument.
The residual is not in the plane of the sky in any interesting way; it is
in the parallax. The object is closing almost radially, so its apparent
position is governed by how far away it is, and the lever arm that turns
a distance error into an angle is the Earth's displacement from the
opposition line. That lever arm goes to zero at opposition, which fell on
11 April, in the middle of our arc. So the fit is perfect in the middle
and wrong at both ends, which is exactly what least squares does when you
put a straight line through a parabola.

A ballistic solution refitted to the whole arc puts the object 0.23 AU
NEARER than it is at the end of April. Fourteen days past opposition the
Earth is 0.238 AU off the line, so at 21.5 AU one AU of distance error is
108 arcseconds of apparent position, and 0.23 AU is 25 of them. No
adjustment of the six elements absorbs it, because it is not an angle.
It is a distance error being read out as one.

Adding one term fixes it completely. Residuals drop to 0.07" RMS, which
is our noise.

    a = 0.0712 +/- 0.0004 m/s^2, radial, anti-sunward, CONSTANT

Anti-sunward on an inbound body is a deceleration. The term is constant
to within our errors across a 7.6 AU change in heliocentric distance,
which is the single most important number in this circular.

    In AU/day^2, 0.0712 m/s^2 is 3.553e-03. That is the number to set
    beside a published cometary A1 of order 1e-08, but the comparison is
    not like for like and we would rather say so than let it pass:
    Marsden's A1 is the coefficient of g(r), and g(25 AU) is 5e-26, so
    expressed properly against that scaling the fitted term would be
    A1 ~ 1e+23. We do not use the g(r) scaling in the fit, because the
    term does not scale.

---------------------------------------------------------------------------

WHY THIS CANNOT BE OUTGASSING

Outgassing is anti-sunward, so the DIRECTION is not the problem. Everything
else is.

    1.  MAGNITUDE. A typical short-period comet's non-gravitational
        acceleration at 1 AU is 2.0e-07 m/s^2. This is 356,000 times
        that, and it is happening at 25 AU, where the standard g(r)
        scaling puts a comet's term some twenty-five orders of magnitude
        below its value at 1 AU.

    2.  IT DOES NOT SCALE. Outgassing tracks insolation. Over our arc
        insolation rose by 80%. The term did not move.

    3.  NO COMA. Deep imaging to 27.4 mag/arcsec^2 shows no extended
        scattering at any epoch, and no gas emission in any of the
        spectra taken so far.

    4.  REACTION MASS. To sustain 0.0712 m/s^2 with an exhaust velocity
        of 1 km/s, which is the best a sublimating ice does, the object
        must eject its own mass in v_exhaust / a = 3.9 hours, whatever
        its mass is. It has been doing this for at least four weeks.

---------------------------------------------------------------------------

ENERGY, AND A MASS

The specific power does not require the mass:

    a x v  =  0.0712 x 5.593e05  =  3.98e04 W/kg  at discovery

Every kilogram of this object is shedding kinetic energy at forty
kilowatts, continuously, and has been for a month.

If that energy is being dissipated rather than transferred, it has to
leave as radiation, and we can put a ceiling on how much radiation there
is without knowing anything at all about the object's shape.

The Hyperion circular measures 1,389 Jy at 70 um and 50.0 K on 4 April.
Integrating that spectrum over the sky gives the apparent bolometric
luminosity - the power the object would be radiating if it radiated
equally in all directions:

    L  =  1.65e16 W

Almost all of that is absorbed sunlight re-emitted, and the Hyperion
circular argues persuasively that all of it is. But as a ceiling we may
credit the whole of it to the deceleration. At the 4 April epoch
a x v is 3.68e04 W/kg, so

    M  <  L / (a x v)  =  4.5e11 kg        (449 million tonnes)

This bound needs no albedo and no equilibrium argument, and it is
generous by whatever fraction of that luminosity is in fact sunlight,
which is probably all of it. It depends on geometry in one place only:
L above is the isotropic-equivalent luminosity, and the true radiated
power is larger by the emitting-to-projected area ratio Hyperion measures
as 4.95, which would put the ceiling at 5.6e11 kg. We quote the tighter
of the two and flag that the looser one exists.

Four hundred and forty-nine million tonnes is less than half a cubic
kilometre of water. Comet 67P/Churyumov-Gerasimenko, which is four
kilometres across, is twenty-two times heavier than this object's upper
limit.

This object is six hundred and eighty-seven thousand kilometres across.

Spread over the PROJECTED area the imaging implies - and that area is a
circle fit, see CVO-Q-26041-0338 - the bound is an areal density of
3.9e-05 kg/m^2, about fifty times a single sheet of graphene. Spread
over the actual curved surface, 4.95 times larger, it is 7.8e-06 kg/m^2,
about ten sheets. Read downward from either as the estimate of what
fraction of the far-infrared is sunlight improves. We think the honest reading is that this is an
enormous, almost massless structure decelerating at seven hundredths of a
metre per second squared, and that neither half of that sentence has an
explanation.

---------------------------------------------------------------------------

PROJECTION, FORWARD

If the term holds, radial velocity reaches zero on

    2026-06-27, at a heliocentric distance of 15.4 AU

after which the solution is undefined, because nothing in the fit says
what happens to a term that exists to remove a velocity once there is no
velocity left to remove.

---------------------------------------------------------------------------

PROJECTION, BACKWARD, AND WHY WE DO NOT BELIEVE IT

Run the same term backwards:

    147 days before discovery      1,464 km/s at   116 AU
    one year before discovery      2,805 km/s at   385 AU
    ten years before discovery    23,013 km/s at 24,876 AU  (0.077 c)

The last line is arithmetic and not physics. A constant term integrated
backwards puts this object at eight percent of the speed of light within
a decade, at which point a Newtonian integration is the wrong tool and
the premise has failed.

The honest reading is that the deceleration began recently and that we
have no fit for when, because we have no observation from before it did.
Deep stacked searches at every backward-integrated position have found
nothing, which is consistent with the object not having been there.

---------------------------------------------------------------------------

We state all of this without interpretation. We have no mechanism to
offer. Eleven observatories agree on the astrometry, one added term
reduces the residuals to the noise, and that term is a hundred thousand
times anything in the literature. Independent fits are invited and our
observations are attached.

===========================================================================
                       END ORBIT SOLUTION
===========================================================================
