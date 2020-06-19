# iq_files

Simplement une sauvegarde de mes capture rtl_sdr de mes télécommandes 433 Mhz

Exemple de capture 
rtl_sdr -s 250000 -g 35 -f 433.716e6 /tmp/on.iq

Exemple de lecture avec rpitx
sudo ./sendiq -s 250000 -f 433.716e6 -t u8 -i /tmp/on.iq

