---
slug: "cvis-dr7-alert-04471"
title: "CVIS automated alert 04471 — a moving source with an impossible colour"
date: 2026-03-28
document_code: "CVIS-DR7-ALERT-04471"
facility: "CERRO VENTANA OBSERVATORY — 1.8 m survey telescope"
author: "CVIS alert pipeline, with duty astronomer annotation"
distribution: "PUBLIC ALERT STREAM"
---

===========================================================================
                   CERRO VENTANA INFRARED SURVEY
                  AUTOMATED ALERT STREAM — CVIS DR7
===========================================================================

ALERT ID            CVIS-DR7-04471
ISSUED              2026-03-28  09:41:07 UT
INSTRUMENT          CVIS wide-field camera, 1.8 m, J H Ks
PIPELINE            cvis-diff v7.2.1  (difference imaging, 5 sigma)
CLASS               UNCLASSIFIED — automatic, unreviewed

---------------------------------------------------------------------------

POSITION (ICRS, epoch of observation)

    RA              13 18 13.85   +/- 0.004 s
    Dec             -08 36 50.0   +/- 0.06 "
    ecliptic lat    -0.33 deg
    solar elong     165.6 deg     (near opposition)

PHOTOMETRY

    BAND    LAMBDA      FLUX          MAG        SNR
    J       1.25 um      2.98 mJy     14.32       41
    H       1.65 um     14.65 mJy     12.11      124
    Ks      2.15 um     38.71 mJy     10.59      265

    J-H = 2.21     H-Ks = 1.52

    The source saturates the nominal Ks integration. The photometry
    above is from the short-exposure calibration frames, whose 5 sigma
    depths are J 16.6, H 15.6, Ks 14.9.

    Source is unresolved. PSF 0.82", seeing limited.

MOTION

    Detected in three consecutive nightly stacks, moving 99 "/day,
    retrograde. The path is dominated by parallax and curves measurably
    over three nights. The parallactic solution gives

        geocentric distance   29.1 +/- 1.4 AU
        heliocentric distance 30.1 AU

---------------------------------------------------------------------------

AUTOMATIC CLASSIFICATION

    Pipeline class:     UNCLASSIFIED / ANOMALOUS
    Nearest template:   none within tolerance
    Flags:              COLOUR_OUT_OF_RANGE, DIST_COLOUR_MISMATCH,
                        NO_ARCHIVAL_COUNTERPART

    The pipeline was unable to assign a class. A blackbody fit to the
    three colours gives 1150 K +/- 90 K. The parallax puts the object
    30.1 AU from the Sun, where an isothermal sunlit body sits at 51 K.

    There is no source at this position in 2MASS, UKIDSS, VISTA/VHS or
    unWISE, to depths five magnitudes below the Ks detection above.

---------------------------------------------------------------------------

DUTY ASTRONOMER ANNOTATION, appended 2026-03-28 11:20 UT

I am forwarding this because the pipeline is required to forward it and
not because I believe it.

A 1150 K source at 30 AU is a factor of twenty-three above equilibrium.
There is no mechanism for it. The nearest thing to a natural explanation
is a cryovolcanic event, and a 200 K surface radiates a thousandth of
what a 1150 K one does.

Before anyone spends time on this I would like the following excluded:
an internal reflection, a warm pixel cluster that survived the flat, a
dewar window artefact, and an uncatalogued red star with a plate-solve
error repeated across three nights. I have ruled out the first and the
third on this instrument. The fourth is the one I would go after,
except that the thing moved 99 arcseconds in a day and stars do not.

If it is real it is the most anomalous thermal source in the outer
system, and it is bright enough that somebody with a real telescope can
settle it in one night. Somebody should, before I put my name on it.

===========================================================================
                         END AUTOMATED ALERT
===========================================================================
