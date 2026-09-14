---
slug: "sed-multiband"
title: "Multiband photometry — two components, and why no single instrument sees both"
date: 2026-06-02
document_code: "SED-2026-K1"
facility: "Compiled, 6 observatories"
author: "Compiled photometry working note"
distribution: "PUBLIC"
---
===========================================================================
                  COMPILED MULTIBAND PHOTOMETRY
                    OBJECT  CVIS-DR7-04471
===========================================================================

EPOCH OF TABLE      2026-04-11
HELIOCENTRIC DIST   25.90 AU        GEOCENTRIC 24.90 AU
MODEL               two components, four measured quantities

---------------------------------------------------------------------------

    BAND     LAMBDA     HOT COMP    COLD COMP       TOTAL      MAG   SRC
               (um)                                          (Vega)
    J          1.25    4.065 mJy    8e-84 mJy   4.065 mJy    13.98    m
    H          1.65    20.01 mJy    8e-61 mJy   20.01 mJy    11.77    m
    Ks         2.15    52.89 mJy    3e-44 mJy   52.89 mJy    10.25    m
    L'         3.78    123.8 mJy    9e-21 mJy   123.8 mJy     8.25    M
    M'         4.68    127.6 mJy    6e-15 mJy   127.6 mJy     7.77    M
    N         10.60    65.68 mJy    0.123 mJy   65.81 mJy     6.88    m
    Q         18.00    30.14 mJy     1.170 Jy    1.201 Jy     2.54    P
    FIR70     70.00    2.628 mJy     1888. Jy    1888. Jy        -    m
    FIR160   160.00    0.530 mJy     1748. Jy    1748. Jy        -    m

    M  measured at this epoch.
    m  measured at another epoch and carried here by the model. J, H and
       Ks were measured on 28 March, the far-infrared on 4 April, N on
       18 April. The object closed 6.0 AU across that span, so
       reprinting any of them at this date would be wrong.
    P  PART measured. The only 18 um observation is CVO-Q-26041-0338,
       whose field is 12.75" and which contains 307 mJy of rim plus the
       30 mJy point source: 0.34 Jy in total, measured. The 1.17 Jy in
       the table is that surface brightness carried over the full 35.7
       arcsec^2 the circle fit implies, which no instrument has imaged.

THE MODEL

    HOT     T = 1150 +/- 90 K      emitting area 6.16e07 m^2
                                   Not solar-heated. Temperature and area
                                   unchanged to within the errors over
                                   nine weeks, so its flux runs as
                                   1/distance^2 and nothing else.

    COLD    projected area 1.16e16 m^2, FIXED, from the 11 April image
                                   T(r) = 264.1 / sqrt(r_AU)
                                   = 51.9 K at this epoch

The four measured quantities are the near-infrared colours (which give
the hot temperature), the near-infrared flux (which gives the hot area),
the 18 um image (which gives the cold area), and the 70/160 ratio (which
gives the cold temperature). Everything else in the table is output.

A NOTE ON THE COLD AREA. It is 35.71 arcsec^2 at this epoch, of which
9.36 was inside the detector and the rest is a circle fitted to the two
arcs and run off the edge of it. The imaging report says so at length and
we repeat it because every cold-component number in this archive scales
linearly with it. It is a fixed PHYSICAL area: as the object closes it
subtends more sky, 26.1 arcsec^2 on 28 March and 48.1 on 25 April, and
the far-infrared fluxes below rise for that reason as well as for the
temperature.

---------------------------------------------------------------------------

WHY THE TWO ORIGINAL REPORTS DISAGREED

    below  4 um     cold component contributes 1e-20 mJy or less, and
                    1e-14 mJy at 4.7 um. A near-infrared survey sees a
                    hot point and correctly reports it unresolved.

    at    18 um     both components measurable in the same data, and
                    separated on the sky by more than the beam. The only
                    such window.

    above 40 um     hot component contributes 2.6 mJy against 1,888 Jy.
                    A far-infrared observatory sees a cold extended
                    source and correctly reports it.

Both are complete accounts of what the instrument can see. Neither is a
complete account of the object.

---------------------------------------------------------------------------

THE COLD COMPONENT IS IN EQUILIBRIUM, AND THAT IS A PREDICTION

There has been some circulation of the idea that the cold component runs
hot and that the excess is the deceleration energy. This is where that
can be settled, and it can be settled with one more observation.

Sunlight alone requires T to scale as one over the square root of the
heliocentric distance, with no free parameter once the 4 April point is
fixed. That gives:

    DATE        r(AU)    T(K)     F(70 um)    F(160 um)
    2026-03-28  30.07    48.2      1,012 Jy     1,090 Jy
    2026-04-04  27.90    50.0      1,389 Jy     1,384 Jy   <- measured
    2026-04-11  25.90    51.9      1,888 Jy     1,748 Jy
    2026-04-25  22.42    55.8      3,373 Jy     2,733 Jy
    2026-05-16  18.51    61.4      7,016 Jy     4,848 Jy
    2026-05-30  16.77    64.5     10,004 Jy     6,414 Jy

One point in that table is measured. The rest has one adjustable number
in it, the normalisation, fixed by that point, and no others.

Now suppose instead that the object is absorbing its own deceleration
energy, at the largest rate the astrometric mass bound allows: the whole
of ORB-2026-K1's 4.5e11 kg, shedding a x v. That power falls as the
object slows, while sunlight rises as it closes, so the two models are
furthest apart when the object is far and converge as it arrives. Fixed
to the same 4 April point, the deceleration model predicts

    2026-05-30      6,000 Jy at 70 um

against 10,000 for sunlight alone. That is a factor of 1.7 and it is not
a subtle measurement. A single far-infrared pointing at the end of May
distinguishes them, and we would be glad if somebody took it.

---------------------------------------------------------------------------

BRIGHTENING, L' BAND

    DATE          GEO DIST (AU)     FLUX (mJy)
    2026-03-28        29.10            90.6
    2026-04-04        26.90           106.1
    2026-04-11        24.90           123.8
    2026-04-25        21.45           166.8
    2026-05-16        17.69           245.3
    2026-05-30        16.11           295.6

The hot component's flux scales as the inverse square of the geocentric
distance across the whole series, to within the errors. It has not
changed temperature, or size, or output, in the nine weeks we have been
watching it.

It is getting closer, and that is all it is doing.

===========================================================================
                          END COMPILATION
===========================================================================
