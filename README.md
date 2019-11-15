Run the test to generate the mock "example.h"

```
$> ceedling clobber test:all
```

The generated header is in build/test/mocks/example.h

It should have transformed all inline functions to regular functions that can be mocked.
```
uint16_t alwaysinline_func_0 (uint32_t a);
uint16_t alwaysinline_func_1 (uint32_t a);
uint16_t alwaysinline_func_2 (uint32_t a);
uint16_t alwaysinline_func_3 (uint32_t a);
uint16_t alwaysinline_func_4 (uint32_t a);
uint16_t alwaysinline_func_5 (uint32_t a);
uint16_t alwaysinline_func_6 (uint32_t a);
uint16_t alwaysinline_func_7 (uint32_t a);
uint16_t alwaysinline_func_8 (uint32_t a);
uint16_t alwaysinline_func_9 (uint32_t a);
uint16_t alwaysinline_func_10 (uint32_t a);
uint16_t alwaysinline_func_11 (uint32_t a);
uint16_t alwaysinline_func_12 (uint32_t a);
uint16_t alwaysinline_func_13 (uint32_t a);
uint16_t alwaysinline_func_14 (uint32_t a);
uint16_t alwaysinline_func_15 (uint32_t a);
uint16_t inline_func_0 (uint32_t a);
uint16_t inline_func_1 (uint32_t a);
uint16_t inline_func_2 (uint32_t a);
uint16_t inline_func_3 (uint32_t a);
uint16_t inline_func_4 (uint32_t a);
uint16_t inline_func_5 (uint32_t a);
uint16_t inline_func_6 (uint32_t a);
uint16_t inline_func_7 (uint32_t a);
uint16_t inline_func_8 (uint32_t a);
uint16_t inline_func_9 (uint32_t a);
uint16_t inline_func_10 (uint32_t a);
uint16_t inline_func_11 (uint32_t a);
uint16_t inline_func_12 (uint32_t a);
uint16_t inline_func_13 (uint32_t a);
uint16_t inline_func_14 (uint32_t a);
uint16_t inline_func_15 (uint32_t a);
uint16_t inline_func_16 (uint32_t a);
```