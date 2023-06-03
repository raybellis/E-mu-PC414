README
======

These are PCB design files for reproduction E-mu PC414 encoder PCBs
as used in various members of the E-mu E4 rack sampler range.

These PCBs have additional pads for fitting a pair of 1µF 0805
capacitors that are intended to reduce transients that might
cause the encoder to jump sporadically, as described by Jörg Sigle
at https://www.jsigle.com/musicol/emufix.htm

If you do not with to fit these capacitors then the boards will
work the same as the E-mu originals.

The required encoder is the Bourns ECW0D-C24-BD0009L.  This is
exactly the same as the original part with the exception of the L
suffix that denotes RoHS compatibility.  NB: this is a 1:4 ratio
encoder - it has 36 detents per revolution but each detent only
generates a quarter of a full Gray code quadrature cycle.

Model Compatibility
-------------------

Some later-built models use a different PCB (PC10395) which holds
a smaller (16mm^2) 24 PPR encoder.

The easiest way to tell which model board you need is to remove the
knob from the encoder shaft and see what's behind.  The 16mm square
encoder used on the PC10395 board is easy to recognise.  The larger
Bourns encoder *should* have a metal ball bearing screwed onto the
encoder's thread which should be transplanted onto your new encoder.

The front panel's mounting posts for the PC10395 PCB are above and
below the encoder hole, instead of to the left and right.  If your
front panel has both sets of mounting posts present then it _may_
be possible to use the PC414 board instead, but you will need to
run the encoder calibration procedure.

License
-------

These files are published under a BY-NC-SA license.  This allows for
non-commercial use, and requires that any derivative works be shared
under the same terms.

If you want to make and distribute these commercially please contact
me.  I'm in most of the E-mu groups on Facebook.
