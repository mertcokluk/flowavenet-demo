# FloWaveNet Demo Page

**Note:** Audio embedding is not enabled in Markdown. For your convenience open .html demo file by means of a browser and enjoy the demo. 

<div>
  
## Model Comparisons

<table>

<tbody>

<tr>

<td colspan="5"><span>Ground Truth</span></td>

</tr>

<tr>

<td>
  
[Sample 1](https://raw.githubusercontent.com/mertcokluk/flowavenet-demo/master/samples/GT/1.wav)

</td>

<td>

[Sample 2](https://raw.githubusercontent.com/mertcokluk/flowavenet-demo/master/samples/GT/2.wav)

</td>

<td>

[Sample 3](https://raw.githubusercontent.com/mertcokluk/flowavenet-demo/master/samples/GT/3.wav)

</td>

<td>

[Sample 4](https://raw.githubusercontent.com/mertcokluk/flowavenet-demo/master/samples/GT/4.wav)

</td>

<td>

[Sample 5](https://raw.githubusercontent.com/mertcokluk/flowavenet-demo/master/samples/GT/5.wav)

</td>

</tr>

<tr>

<td colspan="5"><span>Autoregressive WaveNet (Mixture of Logistics)</span></td>

</tr>

<tr>

<td>

[Sample 1](https://raw.githubusercontent.com/mertcokluk/flowavenet-demo/master/samples/MoL/1.wav)

</td>

<td>

[Sample 2](https://raw.githubusercontent.com/mertcokluk/flowavenet-demo/master/samples/MoL/2.wav)

</td>

<td>

[Sample 3](https://raw.githubusercontent.com/mertcokluk/flowavenet-demo/master/samples/MoL/3.wav)

</td>

<td>

[Sample 4](https://raw.githubusercontent.com/mertcokluk/flowavenet-demo/master/samples/MoL/4.wav)

</td>

<td>

[Sample 5](https://raw.githubusercontent.com/mertcokluk/flowavenet-demo/master/samples/MoL/5.wav)

</td>

</tr>

<tr>

<td colspan="5"><span>Autoregressive WaveNet (A single Gaussian)</span></td>

</tr>

<tr>

<td>

[Sample 1](https://raw.githubusercontent.com/mertcokluk/flowavenet-demo/master/samples/Gaussian/1.wav)

</td>

<td>

[Sample 2](https://raw.githubusercontent.com/mertcokluk/flowavenet-demo/master/samples/Gaussian/2.wav)

</td>

<td>

[Sample 3](https://raw.githubusercontent.com/mertcokluk/flowavenet-demo/master/samples/Gaussian/3.wav)

</td>

<td>

[Sample 4](https://raw.githubusercontent.com/mertcokluk/flowavenet-demo/master/samples/Gaussian/4.wav)

</td>

<td>

[Sample 5](https://raw.githubusercontent.com/mertcokluk/flowavenet-demo/master/samples/Gaussian/5.wav)

</td>

</tr>

<tr>

<td colspan="5"><span>Gaussian IAF</span></td>

</tr>

<tr>

<td>

[Sample 1](https://raw.githubusercontent.com/mertcokluk/flowavenet-demo/master/samples/IAF/1.wav)

</td>

<td>

[Sample 2](https://raw.githubusercontent.com/mertcokluk/flowavenet-demo/master/samples/IAF/2.wav)

</td>

<td>

[Sample 3](https://raw.githubusercontent.com/mertcokluk/flowavenet-demo/master/samples/IAF/3.wav)

</td>

<td>

[Sample 4](https://raw.githubusercontent.com/mertcokluk/flowavenet-demo/master/samples/IAF/4.wav)

</td>

<td>

[Sample 5](https://raw.githubusercontent.com/mertcokluk/flowavenet-demo/master/samples/IAF/5.wav)

</td>

</tr>

<tr>

<td colspan="5"><span>FloWaveNet</span></td>

</tr>

<tr>

<td>

[Sample 1](https://raw.githubusercontent.com/mertcokluk/flowavenet-demo/master/samples/FWN/1.wav)

</td>

<td>

[Sample 2](https://raw.githubusercontent.com/mertcokluk/flowavenet-demo/master/samples/FWN/2.wav)

</td>

<td>

[Sample 3](https://raw.githubusercontent.com/mertcokluk/flowavenet-demo/master/samples/FWN/3.wav)

</td>

<td>

[Sample 4](https://raw.githubusercontent.com/mertcokluk/flowavenet-demo/master/samples/FWN/4.wav)

</td>

<td>

[Sample 5](https://raw.githubusercontent.com/mertcokluk/flowavenet-demo/master/samples/FWN/5.wav)

</td>

</tr>

</tbody>

</table>

</div>

<div>
  
## Temperature Effect on Audio Quality Trade-off 

### Sample 1 (T = 0.0 ~ 1.0) ![temperature gif](images/Temperature.gif)

<table>

<thead>

<tr>

<th>T = 0.0</th>

<th>T = 0.5</th>

<th>T = 0.8</th>

<th>T = 1.0</th>

</tr>

</thead>

<tbody>

<tr>

<td colspan="4"><span>Sample 1</span></td>

</tr>

<tr>

<td>

[Sample 0.0](https://raw.githubusercontent.com/mertcokluk/flowavenet-demo/master/samples/FWN/temp/1_0.0.wav)

</td>

<td>


[Sample 0.5](https://raw.githubusercontent.com/mertcokluk/flowavenet-demo/master/samples/FWN/temp/1_0.5.wav)

</td>

<td>


[Sample 0.8](https://raw.githubusercontent.com/mertcokluk/flowavenet-demo/master/samples/FWN/temp/1_0.8.wav)

</td>

<td>


[Sample 1.0](https://raw.githubusercontent.com/mertcokluk/flowavenet-demo/master/samples/FWN/temp/1_1.0.wav)

</td>

</tr>

<tr>

<td colspan="4"><span>Sample 2</span></td>

</tr>

<tr>

<td>

[Sample 0.0](https://raw.githubusercontent.com/mertcokluk/flowavenet-demo/master/samples/FWN/temp/2_0.0.wav)

</td>

<td>
  
[Sample 0.5](https://raw.githubusercontent.com/mertcokluk/flowavenet-demo/master/samples/FWN/temp/2_0.5.wav)

</td>

<td>

[Sample 0.8](https://raw.githubusercontent.com/mertcokluk/flowavenet-demo/master/samples/FWN/temp/2_0.8.wav)

</td>

<td>

[Sample 1.0](https://raw.githubusercontent.com/mertcokluk/flowavenet-demo/master/samples/FWN/temp/2_1.0.wav)

</td>

</tr>

<tr>

<td colspan="4"><span>Sample 3</span></td>

</tr>

<tr>

<td>

[Sample 0.0](https://raw.githubusercontent.com/mertcokluk/flowavenet-demo/master/samples/FWN/temp/3_0.0.wav)

</td>

<td>

[Sample 0.5](https://raw.githubusercontent.com/mertcokluk/flowavenet-demo/master/samples/FWN/temp/3_0.5.wav)

</td>

<td>

[Sample 0.8](https://raw.githubusercontent.com/mertcokluk/flowavenet-demo/master/samples/FWN/temp/3_0.8.wav)

</td>

<td>

[Sample 1.0](https://raw.githubusercontent.com/mertcokluk/flowavenet-demo/master/samples/FWN/temp/3_1.0.wav)

</td>

</tr>

</tbody>

</table>

</div>

<div>
  
## Analysis of ClariNet Loss Terms 

### Gaussian IAFs (Only KL, KL + Frame, Only Frame) Iterations 50K ~ 500K

<table>

<thead>

<tr>

<th>Only KL</th>

<th>KL + Frame</th>

<th>Only Frame</th>

</tr>

</thead>

<tbody>

<tr>

<td colspan="3"><span></span></td>

</tr>

<tr>

<td>

![kl gif](images/Only%20KL.gif)</td>

<td>
  
![kl+frame gif](images/KL+Frame.gif)</td>

<td>
  
![frame gif](images/Only%20Frame.gif)</td>

</tr>

</tbody>

</table>

<table>

<thead>

<tr>

<th>50K</th>

<th>110K</th>

<th>130K</th>

<th>200K</th>

<th>250K</th>

<th>500K</th>

</tr>

</thead>

<tbody>

<tr>

<td colspan="6"><span>Only KL</span></td>

</tr>

<tr>

<td>

[Sample 50k](https://raw.githubusercontent.com/mertcokluk/flowavenet-demo/master/samples/IAF/KL_50K.wav)

</td>

<td>

[Sample 110k](https://raw.githubusercontent.com/mertcokluk/flowavenet-demo/master/samples/IAF/KL_110K.wav)

</td>

<td>

[Sample 130k](https://raw.githubusercontent.com/mertcokluk/flowavenet-demo/master/samples/IAF/KL_130K.wav)

</td>

<td>

[Sample 200k](https://raw.githubusercontent.com/mertcokluk/flowavenet-demo/master/samples/IAF/KL_200K.wav)

</td>

<td>

[Sample 250k](https://raw.githubusercontent.com/mertcokluk/flowavenet-demo/master/samples/IAF/KL_250K.wav)

</td>

<td>

[Sample 500k](https://raw.githubusercontent.com/mertcokluk/flowavenet-demo/master/samples/IAF/KL_500K.wav)

</td>

</tr>

<tr>

<td colspan="6"><span>KL + Frame</span></td>

</tr>

<tr>

<td>

[Sample 50k](https://raw.githubusercontent.com/mertcokluk/flowavenet-demo/master/samples/IAF/KL_Frame_50K.wav)

</td>

<td>

[Sample 110k](https://raw.githubusercontent.com/mertcokluk/flowavenet-demo/master/samples/IAF/KL_Frame_110K.wav)

</td>

<td>

[Sample 130k](https://raw.githubusercontent.com/mertcokluk/flowavenet-demo/master/samples/IAF/KL_Frame_130K.wav)

</td>

<td>

[Sample 200k](https://raw.githubusercontent.com/mertcokluk/flowavenet-demo/master/samples/IAF/KL_Frame_200K.wav)

</td>

<td>

[Sample 250k](https://raw.githubusercontent.com/mertcokluk/flowavenet-demo/master/samples/IAF/KL_Frame_250K.wav)

</td>

<td>

[Sample 500k](https://raw.githubusercontent.com/mertcokluk/flowavenet-demo/master/samples/IAF/KL_Frame_500K.wav)

</td>

</tr>

<tr>

<td colspan="6"><span>Only Frame</span></td>

</tr>

<tr>

<td>

[Sample 50k](https://raw.githubusercontent.com/mertcokluk/flowavenet-demo/master/samples/IAF/Frame_50K.wav)

</td>

<td>

[Sample 110k](https://raw.githubusercontent.com/mertcokluk/flowavenet-demo/master/samples/IAF/Frame_110K.wav)

</td>

<td>

[Sample 130k](https://raw.githubusercontent.com/mertcokluk/flowavenet-demo/master/samples/IAF/Frame_130K.wav)

</td>

<td>

[Sample 200k](https://raw.githubusercontent.com/mertcokluk/flowavenet-demo/master/samples/IAF/Frame_200K.wav)

</td>

<td>

[Sample 250k](https://raw.githubusercontent.com/mertcokluk/flowavenet-demo/master/samples/IAF/Frame_250K.wav)

</td>

<td>

[Sample 500k](https://raw.githubusercontent.com/mertcokluk/flowavenet-demo/master/samples/IAF/Frame_500K.wav)

</td>

</tr>

</tbody>

</table>

</div>

<div>
  
## Causality of WaveNet Dilated Convolutions

<table>

<tbody>

<tr>

<td colspan="5"><span>FloWaveNet (Non-causal)</span></td>

</tr>

<tr>

<td>

[Sample 1](https://raw.githubusercontent.com/mertcokluk/flowavenet-demo/master/samples/FWN/1.wav)

</td>

<td>

[Sample 2](https://raw.githubusercontent.com/mertcokluk/flowavenet-demo/master/samples/FWN/2.wav)

</td>

<td>

[Sample 3](https://raw.githubusercontent.com/mertcokluk/flowavenet-demo/master/samples/FWN/3.wav)

</td>

<td>

[Sample 4](https://raw.githubusercontent.com/mertcokluk/flowavenet-demo/master/samples/FWN/4.wav)

</td>

<td>

[Sample 5](https://raw.githubusercontent.com/mertcokluk/flowavenet-demo/master/samples/FWN/5.wav)

</td>

</tr>

<tr>

<td colspan="5"><span>FloWaveNet (Causal)</span></td>

</tr>

<tr>

<td>

[Sample 1](https://raw.githubusercontent.com/mertcokluk/flowavenet-demo/master/samples/FWN/1_causal.wav)

</td>

<td>

[Sample 2](https://raw.githubusercontent.com/mertcokluk/flowavenet-demo/master/samples/FWN/2_causal.wav)

</td>

<td>

[Sample 3](https://raw.githubusercontent.com/mertcokluk/flowavenet-demo/master/samples/FWN/3_causal.wav)

</td>

<td>

[Sample 4](https://raw.githubusercontent.com/mertcokluk/flowavenet-demo/master/samples/FWN/4_causal.wav)

</td>

<td>

[Sample 5](https://raw.githubusercontent.com/mertcokluk/flowavenet-demo/master/samples/FWN/5_causal.wav)

</td>

</tr>

</tbody>

</table>

</div>
