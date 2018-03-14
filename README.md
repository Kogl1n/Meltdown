# Meltdown

The difference of this version compared to IAIK/Meltdown is that it incorporates the following idea:
"Making it work on uncached memory is trickier, and often requires a bit of tweaking of the parameters. Thus, we ensure that the memory is cached in the PoC to make it easier to reproduce. However, you can simply remove the code that caches the values and replace it by a `clflush` to test the exploit on uncached memory (see Video #5 for an example).
    Although not in the original blog post by Google, this was also confirmed by independent researchers"

# Spectre impact on AMD:
https://amdflaws.com/
