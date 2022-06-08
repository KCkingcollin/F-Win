# F-Win (Functionally Windows)
The "Functionally Windows" or "Func Win" project is currently a concept/pipe dream at the moment that involves doing something similar to what wine does but backwards.

Instead of building ground up this projects intentions are to slowly replace software in a emulated windows environment with a sort of API bridge through a virtual device and into host side applications, and to continue replacing files until we don't need the virtual environment anymore.

Obviously we will start with a completely stripped down version of the windows iso with only the applications that are absolutely required for operation, unfortunately that means anybody wanting to test this project will have to download and modify thier own windows iso (due to legal reasons), but i promises ill try to make this process as painless as the law will allow me.

## Goals of this project

- [x] #1. Decide on a version of Windows and get it in a virtual environment

Going with windows 10 for now

- [ ] #2. Find out just how much software we can RIP out of our windows install while keeping it running smoothly

- [ ] #3. Code up our virtual API bridge (VAB)

- [ ] #4. Pass through, and convert Nvidia, AMD, and Intel graphics API to their respective Linux equivalents (this should also be the stage we start putting focus on game compatibility)

- [ ] #5. Replace windows plug and play device control with Linux via VAB

- [ ] #6. Create a driver for ext4 and btrfs support likely utilizing VAB

- [ ] #6.5 Start working on an automatable emulation platform that isn't reliant on virtualization of cpu cores

- [ ] #6.5.5 Release the first standalone stable build of the project (possibly releasing pre built packages if we can get around MS copyright some how)

- [ ] #7. Release windows from the confineds of a disk image and remove the VAB dependency

- [ ] #8. Begin replacing every windows application with open source Linux equivalents until were left with only the ability to run .exe files 

- [ ] #9. Replace the windows kernel (and any left overs), with open source code (potentially utilizing wine code or working with the wine team)

- [ ] #10. Work out the kinks and implement into every linux distro so no one ever has to use the hot garbage that is Microsoft Windows ever again (possibly implementing into steam at some point)

disclaimer: all the code in this project will be open source, and NO infringement will find its way into this project knowingly.
