# Backend OpenGL ES 3.1 (GPU) do MineBitcoinMobile

Plano B para aparelhos sem Vulkan. Usa um compute shader (OpenGL ES 3.1), com o
mesmo algoritmo do backend Vulkan. O app tenta Vulkan primeiro e, se não der,
OpenGL ES. Se nenhum passar no auto-teste (bloco gênese do Bitcoin), usa a CPU.

Aparelhos só com OpenGL ES 3.0 (sem 3.1) não têm compute shader e ficam na CPU.

Para compilar tudo (Vulkan + OpenGL ES, 64 e 32 bits), rode `Native\build_all_wjfpv.bat`.
