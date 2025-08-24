## Estruturas de pastas ##


/
├─ flows/                    # Fluxos do Node-RED (.json)
│  └─ model3d.flow.json
├─ comfy/                    # Workflows ComfyUI/Automatic1111
│  └─ workflows/sdxl_modelsheets.json
├─ prompts/                  # Templates de prompts (YAML/MD)
│  ├─ modelsheet.yml
│  └─ styles/stylized_wildrift.md
├─ scripts/
│  ├─ modelsheet/layout.py   # monta frente/lado/costas/topo em uma folha
│  ├─ recon/triposr_run.py
│  ├─ recon/wonder3d_run.py
│  ├─ post/blender_post.py   # limpeza + export GLB
│  └─ post/pack_gltf.sh      # gltfpack
├─ configs/
│  └─ pipeline.default.yml   # caminhos, opções, modelo padrão
├─ docker/
│  └─ compose.yml            # node-red + comfyui (opcional)
├─ outputs/
│  ├─ sheets/
│  └─ models/
└─ README.md
