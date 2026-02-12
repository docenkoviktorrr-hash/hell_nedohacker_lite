# COCO## SYSTEM INVERT PULSE

Experimental Windows GDI screen inversion demo.

# >WARNING<
This program creates rapid full-screen flashing effects.
Do NOT run if you are sensitive to flickering light.

# >HEALTH<
Do NOT use if you:
- Have epilepsy
- Have photosensitive seizures
- Experience migraines from flashing

If discomfort occurs:
1. Close via Task Manager
2. Or restart the computer

# >WHAT_IT_DOES<
- Captures desktop framebuffer
- Inverts pixels
- Runs timed flashing loop

# >NO_PERSISTENCE<
- No registry edits
- No startup entries
- No system file modification
- Fully stops after reboot

# >BUILD<
g++ coco_system_hell.cpp -o coco_system_hell.exe -O2 -lgdi32 -luser32
