# SBC Benchmark
SBC Benchmarking Information Catalog

## Repo Structure

Each folder has full results and the Data folder has the consolidated information in JSON
format.

## Testing Methodology

Each board is tested with a native image supplied by the manufacturer. If available, test is done with a "server" and a "desktop" image.

File naming convention is \<board make\>\_\<board model\>\_\<OS\>_\<server/desktop\>\_\<test\>.txt

Test is ran with a brand new image, before installing any new software that doesn't automatically comes with the image. Images are updated with most current packages.

It would be awesome to use the same image on all boards but that's not possible in the SBC space.

Power usage information for desktop image is tested with board connected to a single monitor, wired mouse and keyboard. Wifi+BT is turned on if present onboard. I use the same power surce and power cable whem possible.

Power usage information for server image is tested with board connected to Ethernet cable only or Wifi for boards that don't have an ethernet port (ie. Pi Zero).