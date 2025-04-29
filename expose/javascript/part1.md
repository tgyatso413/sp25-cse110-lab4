1. values added: (value of variable result)
2. final result: (value of variable result) 
3. var are visible through blocks, so emulating block-level visibility would requite IIFE.
4. values added: (value of variable result)
5. The code returns an error because keyword let have block-level visibility. result's value only exists in the if block.
6. The code returns an error because a const cannot be reassigned a value.
7. Same as above - const cannot be reassigned.