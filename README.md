# Screen Space Ambient Occlusion



In order to estimate the amount of hemispherical occlusion for each pixel, we utilised a method called Screen Space Ambient Occlusion (SSAO), which involves examining the z-buffer for nearby depth values. Essentially, we sought to determine the degree to which the hemisphere was obstructed and attenuated the intensity of the diffuse indirect lighting by that.
