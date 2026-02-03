Shakespeare CTF – Official Writeup

Challenge Name: The False Soliloquy
Category: Misc / Esoteric Programming Language
Difficulty: Medium

Step 1: Executing the Provided Code

The provided Shakespeare Programming Language (SPL) source code is executed using the online interpreter available at https://esolangpark.vercel.app/ide/shakespeare. Upon initial execution, the program produces theatrical dialogue but does not directly reveal the flag, indicating that the output is intentionally misleading or incomplete.

Step 2: Normalizing Character Names and Forcing Output

The source code contains unauthorized character names that are not supported by the Shakespeare interpreter. These character names must be replaced with valid ones for proper execution. Additionally, several arithmetic computations are performed internally without printing their results. By inserting the statement “Speak your mind!” at the appropriate locations, the hidden computed values are forced to print to the output.

Step 3: Retrieving the Flag

After correcting the character names and adding the required output statements, the program is executed again. This time, the output clearly reveals the flag.

Flag

hacks{H3ll0_c1ph3r}
