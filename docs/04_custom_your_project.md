# Custom Project Configuration

You can edit all properties in `Move.toml`.
```yaml
# project name of Move Project
project_name = 'move-project'
# project root
home = 'sample'

[workspace]
script_dir = 'src/scripts'
module_dir = 'src/modules'
target_dir = 'target'

[compile]
output_source_map = true
output_move_bytecode = true
skip_stdlib = false
custom_stdlib = false
custom_stdlib_path = 'src/stdlib'

[tx]
address = 'cf1fe4b268ee11f5eb2cfbd7279cd789'
keypair_private_key = 'e8fcbecaeeb1e6a2209feedc4d38691709f6f3c85c9f5d15f8fc2a10f4f52362'
keypair_public_key = '98a29c183b9f8b3dc5574eedfad67e8a182fdedd39e6fedda7b45e6efa9ab8e3'
sequence_number = 0

[storage]
load_state_from_genesis = false
save_writeset_to_genesis = false
``` 