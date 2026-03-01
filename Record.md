# Qualcomm Hexagon NPU Architectures

| Snapdragon | NPU Architectures |
|------------|-------------------|
| 8 Gen 1    | v69               |
| 8 Gen 2    | v71               |
| 8 Gen 3    | v73               |
| 8 Elite    | v75               |
| 8 Gen 5    | v81               |


# Create Env
```conda create --name hexagon python=3.11```

Device: OnePlus 15 Snapdragon 8 Gen 5

```export HEXAGON_ARCH_VERSION=81```

Total Discovered Tests: 96
Unsupported:  1 (1.04%)
Passed     : 95 (98.96%)
Local build script completed successfully.

UNSUPPORTED: LINALG-HEXAGON :: Conversion/LinalgToLLVM/vector_size.mlir (73 of 96)

