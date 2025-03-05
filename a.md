# windows

## create dx12 device
https://microsoft.github.io/windows-docs-rs/doc/windows/Win32/Graphics/Direct3D12/struct.ID3D12Device.html

## use dx12 device to create hal device
https://docs.rs/wgpu-core/latest/wgpu_core/global/struct.Global.html#method.create_device_from_hal

## use hal device to create core device
https://github.com/gfx-rs/wgpu/blob/1ea5498038b2fd0392bd6cbd81ec71b2438e5c95/wgpu-hal/src/dx12/device.rs#L31


# Vulkan

## create vulkan device
https://docs.rs/ash/0.38.0+1.3.281/ash/struct.Instance.html#method.create_device

## use vulkan device to create hal device
https://docs.rs/wgpu-hal/latest/wgpu_hal/vulkan/struct.Adapter.html#method.device_from_raw

## use hal device to create core device
https://docs.rs/wgpu-core/latest/wgpu_core/global/struct.Global.html#method.create_device_from_hal
