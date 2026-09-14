---
slug: "optical-nondetection"
title: "Optical non-detection — the object does not reflect"
date: 2026-04-20
document_code: "OPT-2026-K1-NULL"
facility: "CERRO VENTANA OBSERVATORY — 8.2 m"
author: "CVO time-domain group"
distribution: "PUBLIC"
---
===========================================================================
                     CERRO VENTANA OBSERVATORY
                  8.2 m  —  OPTICAL NON-DETECTION
===========================================================================

OBSERVED            2026-04-18 / 2026-04-19, two half-nights
BAND                r'
INTEGRATION         7,200 s, non-sidereal tracking at 164 "/day
SEEING              0.75"  median      SOLAR ELONGATION 173 deg
DEPTH               r' = 26.10   5 sigma, point source
RESULT              NO DETECTION

---------------------------------------------------------------------------

WHY WE LOOKED

At 18 um the object presents, inside the field that imaged it on
11 April, 3.05e15 m^2 of surface. It has closed 1.8 AU since, so at
23.08 AU that same patch subtends 10.89 arcsec^2. We use it and not the
35.7 arcsec^2 the circle fit implies, because we want a limit we can
defend, and the smaller area gives the weaker limit.

Anything with that much surface, that close, ought to be trivial in
reflected sunlight. For real solar system albedos it would be:

    geometric albedo 0.67 (Europa)                       r' = 5.63
    geometric albedo 0.10 (Ceres)                        r' = 7.70
    geometric albedo 0.04 (typical cometary nucleus)     r' = 8.69
    geometric albedo 0.02 (the darkest surfaces known)   r' = 9.45

Every one of those is a binocular object. We went in expecting to measure
a lightcurve and a rotation period.

---------------------------------------------------------------------------

WHAT WE GOT

Nothing, at either epoch, at the ephemeris position, to any depth we can
reach.

The position is not in doubt. The same telescope imaged the thermal
source at 18 um eight nights earlier, the orbit solution including the
fitted deceleration reproduces our own astrometry to 0.07" RMS, and the
ephemeris uncertainty over this interval is smaller than the seeing disc.
We were looking at the right piece of sky.

THE LIMIT, DONE PROPERLY. The source is not a point, so the point-source
depth is the wrong number to use and using it would overstate our result
by a factor of four. What we ran is a matched filter, with the 18 um rim
morphology from CVO-Q-26041-0338 as the template, over the region that
frame imaged. In 0.75" seeing the effective resolution element is
0.64 arcsec^2, so 10.89 arcsec^2 of template covers 17.1 of them and the
noise on the integrated flux is sqrt(17.1) larger — a penalty of 1.54
magnitudes:

    5 sigma point-source depth                   r' = 26.10
    5 sigma limit on the TOTAL reflected flux    r' = 24.56
    5 sigma limit on the geometric albedo        p < 1.8e-08

Carrying the extrapolated area instead of the imaged one would give
p < 9.2e-09. A plain aperture over the whole envelope, with no template,
would be shallower than either and we have not used it. The figure below
is the matched filter on the imaged area: the most conservative of the
three that use the data properly.

---------------------------------------------------------------------------

WHAT THAT NUMBER MEANS

    darkest natural surface measured in the solar system     2e-02
    darkest material ever manufactured (aligned CNT array)   3.5e-04
    this object                                            < 1.8e-08

The limit is a million times below anything in the solar system and
nineteen thousand times below the darkest substance that has ever been
made in a laboratory.

WHAT IT DOES NOT MEAN. It is not confirmation of the thermal result and
we want to be exact about that, because the two have been quoted together
in places where they should not be. A temperature measured to 1 K at
50 K constrains the Bond albedo only to within a few tenths, and at this
object it does not even do that, because the temperature is dominated by
a geometry factor nobody has measured. It cannot see the difference
between a surface that reflects a percent and one that reflects nothing.
The optical limit is seven orders of magnitude stronger than anything the
far-infrared can say. It is not a confirmation. It is the only
measurement of this quantity that exists.

We are aware that a limit is not a detection, and that the usual meaning
of a limit this severe is that the thing was not where we looked. It was
where we looked. It was on the same mountain eight nights earlier, at
0.34 Jy at 18 um, in a frame that resolves it.

Whatever this is, it does not reflect light. It takes it.

===========================================================================
                       END NON-DETECTION REPORT
===========================================================================
