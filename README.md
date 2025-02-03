# Communication Lab Final - Ekert Circuit

- `eavesdrop = 0`: `None, 1`: three qubits entanglement, 2: intercept-resend
- 每一個 round 的電路放在 game，使用的 basis (choice) belongs to `[0, 1, 2] -> [0, pi/4, pi/2]` or `[0, pi/4, -pi/4]`，出來的結果在 output
- `key` 跟 `s_val` 存在 class 裡面，如果兩邊 `key` 有不同會印 warning
