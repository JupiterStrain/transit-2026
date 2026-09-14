---
slug: "hyperion-circular-2026-118"
title: "Hyperion circular 2026-118 — far-infrared counterpart, and a disagreement"
date: 2026-04-04
document_code: "HYPERION-CIRC-2026-118"
facility: "HYPERION far-infrared observatory (0.85 m, L2)"
author: "Hyperion science operations"
distribution: "PUBLIC"
---

===========================================================================
                  HYPERION FAR-INFRARED OBSERVATORY
                       CIRCULAR  2026-118
===========================================================================

ISSUED              2026-04-04  17:02 UT
TARGET              CVIS-DR7-04471
INSTRUMENT          Hyperion/FIR, 70 um and 160 um
BEAM                20.7" at 70 um, 47.4" at 160 um  (0.85 m, diffraction
                    limited)
FIELD OF REGARD     55 - 180 deg solar elongation (articulated shield).
                    This target is at 173 deg and inside it.
MODE                3' x 3' map, 1,800 s, ARRAY IN LOW GAIN

---------------------------------------------------------------------------

RESULT

    BAND        FLUX (90" aperture)      CALIBRATION
    70 um       1,389 Jy  +/- 5%         Mars, same setting, same week
    160 um      1,384 Jy  +/- 5%         Mars, same setting, same week

Before anything else in this circular is read: that is not a misprint and
it is not a unit error. The source saturated the array in our nominal
setting on the first pass. The photometry above is from a repeat
observation in the low-gain bright-source mode we normally use for
planets, cross-calibrated against Mars in the same configuration and in
the same week.

At 70 um this is now among the brightest compact sources in the sky. It
was not there before. IRAS and AKARI both surveyed this position and both
are blank to their limits, which are three orders of magnitude below what
we measure today.

The source is EXTENDED. Deconvolved against the 70 um beam it is
35" +/- 3" along its long axis and elongated about 2:1. We cannot say
anything more with a 20.7" beam, and we are not going to try.

---------------------------------------------------------------------------

TEMPERATURE, AND HOW THE COLOUR WAS PROTECTED

The two fluxes are equal to within the errors, and that equality is the
whole of our temperature constraint, so the way it was measured matters
more than usual.

Our beam is 2.3 times larger at 160 um than at 70 um, and the source is
larger than either. Unmatched beams on an extended source produce a
colour that is an instrumental artefact and nothing else. We therefore
convolved the 70 um map to the 160 um beam before extracting any
photometry, and used the same 90" aperture on both. The quoted ratio is
beam-matched, not merely aperture-matched.

The 5% calibration error is common to both bands and divides out of the
ratio. What survives is the map noise and the aperture correction:

    F(70)/F(160) = 1.003 +/- 0.040

For a source near 50 K the specific intensity peaks at 102 um, so the two
bands sit either side of the peak and their ratio is a steep function of
temperature. It runs

    0.60 at 40 K        1.00 at 50 K        1.40 at 60 K

    T = 50.0 +/- 1.1 K

---------------------------------------------------------------------------

THE PART WE CANNOT MAKE GO AWAY

A temperature only means something next to a geometry, so here are the
two that bracket the problem. Radiative equilibrium at the object's
heliocentric distance of 27.9 AU is

    isothermal sphere              52.7 K
    thin flat sheet, both faces    62.7 K

We measure 50.0 +/- 1.1 K, which is below both.

Nothing can be colder than equilibrium unless it radiates over more area
than it absorbs over. Our measurement puts the ratio of radiating area to
sunward cross-section at

    A(emitting) / A(cross-section)  =  4.95 +/- 0.44

where a sphere is 4 and a flat sheet is 2. Something with a good deal
more surface than silhouette: folded, or curved, or hollow. We cannot
tell which with a 20.7" beam and we are not going to guess.

What we can say is that the object needs no internal source. It is
consistent with sunlight and geometry and nothing else, and any claim
that it is generating heat has to get past that first. An 8 m in the
8-25 um window can resolve the source and settle its shape in one night.
Until somebody does, the number above is the only handle anyone has on
what shape it is.

---------------------------------------------------------------------------

STATEMENT OF DISAGREEMENT

This result is not compatible with CVIS-DR7-ALERT-04471.

CVIS reports an unresolved source at 1150 K. We report a 35-arcsecond
extended source at 50 K at the same coordinates to within our pointing
accuracy. These are not the same object as described.

We note, without proposing a resolution:

    - our 70 um flux is six orders of magnitude above what a 1150 K
      source of the size CVIS implies would produce in our band;

    - CVIS's Ks flux is forty-nine orders of magnitude above what our
      50 K fit would produce at their epoch and in their band.

Either one of the two photometric solutions is wrong, or the source is
not a single body.

===========================================================================
                          END CIRCULAR
===========================================================================
