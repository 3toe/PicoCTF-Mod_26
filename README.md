# PicoCTF-Mod_26
PicoCTF challenge "Mod 26"

Category: Cryptography

Description: Cryptography can be easy, do you know what ROT13 is? cvpbPGS{arkg_gvzr_V'yy_gel_2_ebhaqf_bs_ebg13_hyLicInt}

How to solve: The flag is provided by encrypted with the ROT13 algo. This can be decoded manually by asigning a value of "1" to "a", "2" to "b" and so on, then adding 13 to each number (wrapping around to 1 after 26) and converting back to alpha characters.

Flag: picoCTF{next_time_I'll_try_2_rounds_of_rot13_ulYvpVag}
