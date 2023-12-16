**THE MOST COMMON ISSUE IN MEMORY MANAGEMENT**

# ¿Which languages ar susceptible?

Many **modern programming languages** dont allow the programmer to allocate or deallocate memory directly.

Therefore those are not prone to memory leaks

However some older ones like C or C++ are

# Cause
Usually caused by **failure to deallocate memory** that has been allocated

Best Defense → A **static code analyzer** can check to see if all memory **allocation** commands have a matching **deallocation** command