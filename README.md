# VIX-contruction
Reproducing the VIX index trough options' IV surface

Following the paper 'Stock return charactersitics, skew laws, and the differential pricing of individual equity options' by G. Bakshi et al. I have reconstructed the VIX index for the period Jan 2016 - Apr 2016 using the options' chain prices and IV. Given the at the VIX index is reproduced using only the options with maturity = 30d, I had to interpolate the IV surface for that specific maturity at each day
