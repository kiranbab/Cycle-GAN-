
_we have not used identity loss here_


# Cycle GAN
    generator loss= LeastSquare Adversarial Loss + Cycle consistency loss + Identity Loss 

Cycle consistentcy loss = Loss calculated when object is converted from one to another class and back to the original class ( Zebra -> Horse -> Zebra ). The reconstructed image should be close to the original image.

Identity Loss = When given a Horse Image in Horse Generator, it shouldm't touch the image and return back the original image This is called as Identity loss(We are using identity loss here)
