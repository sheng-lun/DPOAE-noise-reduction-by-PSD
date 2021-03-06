<h1>This is an example code of Distortion-product otoacoustic emissions(DPOAE) noise reduction by Wiener filter.<br>
</h1> 

<h2>#Written by Sheng-Lun Kao</h2> 

<h3>How to run the code?</h3> 
<p>
Put folder "DPOAE_Data" and code(DPOAE_c_noise reduction_PSD.ipynb) in path C:\   ,then open the code by Jupyter Notebook, run it.
</p>

### [PSD noise reduction]
### - recorded in quiet 34dBA
We hope Wiener filter noise reduction (PSD, green line) as close as possible to the baseline(black line, record DPOAE in quiet), the closer the better.
![image](https://github.com/sheng-lun/DPOAE-noise-reduction-by-PSD/blob/main/Results%20of%20PSD%20reduction%20method/PSD_quiet%2034dBA/Comparison_RA_DPOAE_PSD_34dBA%20quiet.png)

### - recorded in 70 dBA white noise
record DPOAE in noisy (red line)
![image](https://github.com/sheng-lun/DPOAE-noise-reduction-by-PSD/blob/main/Results%20of%20PSD%20reduction%20method/PSD_70%20dBA%20white%20noise/Comparison_RA_DPOAE_PSD_70dBA%20white%20noise.png)

### - recorded in 75 dBA white noise
record DPOAE in noisy (red line)
![image](https://github.com/sheng-lun/DPOAE-noise-reduction-by-PSD/blob/main/Results%20of%20PSD%20reduction%20method/PSD_75%20dBA%20white%20noise/Comparison_RA_DPOAE_PSD_75dBA%20white%20noise.png)

### [Comment]
Obviously, Wiener filter is not a good noise reduction method.
