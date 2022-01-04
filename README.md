<img src="https://i2.wp.com/thisnameismine.com/wp-content/uploads/2021/10/image-edited.png">

#360Diffusion automatically upscales your CLIP Guided Diffusion outputs using Real-ESRGAN.

**Latest revision: Alpha 1.6 (01/03/22):**
https://colab.research.google.com/github/sadnow/360Diffusion/blob/main/360Diffusion_Public.ipynb

*Latest highlights: Critical fixes

Note that 4096 files aren’t quite as pretty as 2048, and they’re massive in file size. 2048 is appealing in most cases. If you intend on upscaling to anything higher than 1024, I recommend using the 512 diffusion model found in the settings-

Credits & Acknowledgements
- Katherine Crowson (https://github.com/crowsonkb, https://twitter.com/RiversHaveWings)	
-  Founder of OG Diffusion Notebook	Original notebook founder; [I think] has a large involvement in both VQGAN and Diffusion! 
- Daniel Russell (https://github.com/russelldc, https://twitter.com/danielrussruss)	Fast Diffusion Fork Founder	Made the OG Fast Diffusion notebook.
- Dango233 and nsheppard		Contributed to Daniel’s Fast Diffusion Notebook
- Sadnow (twitter.com/sadly_existent)	360Diffusion Fork Founder	Forked Daniel Russel’s Fast Diffusion Notebook to include Real-ESRGAN integration-
- airguitararchon (steven)	Init Research	
- Everyone else on the VQLIPSE Discord (https://www.patreon.com/sportsracer48); Support & Research	

Prior release(s): Implemented Daniel Russ’s Perlin revisions, fixed init_bug, 4096 double-pass, VRAM fixes, practical debug_mode (set to higher skip_timestep)

All edits & feedback are welcome and appreciated~
