# library-starter

Features:

- Bundle with [tsup](https://github.com/egoist/tsup)
- Test with [vitest](https://vitest.dev)

# Usage

### 安装

```bash
pnpm add @oiij/three-js
```

### 使用

```vue
<script setup lang="ts">
import { useThreeJs } from '@oiij/three-js'
const { domRef } = useThreeJs()
</script>

<template>
  <div ref="domRef" style="width: 100%; height: 100%;" />
</template>
```

## License

MIT
