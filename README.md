
# DirectX-Graphics-Samples
![D3D12Bundles](./Samples/Desktop/D3D12Bundles/src/D3D12Bundles_small.PNG)
![D3D12HeterogeneousMultiadapte](./Samples/Desktop/D3D12Bundles/src/D3D12HeterogeneousMultiadapte_small.PNG)
![D3D12Multithreading](./Samples/Desktop/D3D12Bundles/src/D3D12Multithreading_small.PNG)
![D3D12nBodyGravity](./Samples/Desktop/D3D12Bundles/src/D3D12nBodyGravity_small.PNG)

This repo contains the DirectX Graphics samples that demonstrate how to build graphics intensive applications for Windows 10. We also have a YouTube channel! Visit us here: https://www.youtube.com/MicrosoftDirectX12andGraphicsEducation

## API Samples
In the Samples directory, you will find samples that attempt to break off specific features and specific usage scenarios into bite sized chunks. For example, the ExecuteIndirect sample will show you just enough about execute indirect to get started with that feature without diving too deep into multiengine whereas the nBodyGravity sample will delve into multiengine without touching on the execute indirect feature etc. By doing this, we hope to make it easier to get started with DirectX 12.

Recent API Sample Updates:
1. D3D12 xGPU: This sample illustrates how to detect and handle a D3D device removed event. Particularly in a case of an external GPU (xGPU) being plugged/unplugged.
2. D3D12 Depth Bounds Test: This sample demos how to use depth bounds test with DirectX 12. In addition, it introduces a more flexible way to create pipeline state, called Pipeline State Object Stream (PSO Stream). PSO Stream is required to use Depth Bounds Test feature.
3. Shader Model 6 Wave Intrinsics: This sample visualizes several new wave intrinsics in Shader Model 6.

## MiniEngine: A DirectX 12 Engine Starter Kit
In addition to the samples, we are announcing the first DirectX 12 preview release of the MiniEngine.

It came from a desire to quickly dive into graphics and performance experiments.  We knew we would need some basic building blocks whenever starting a new 3D app, and we had already written these things at countless previous gigs.  We got tired of reinventing the wheel, so we established our own core library of helper classes and platform abstractions.  We wanted to be able to create a new app by writing just the Init(), Update(), and Render() functions and leveraging as much reusable code as possible.  Today our core library has been redesigned for DirectX 12 and aims to serve as an example of efficient API usage.  It is obviously not exhaustive of what a game engine needs, but it can serve as the cornerstone of something new.  You can also borrow whatever useful code you find.

### Some features of MiniEngine
* High-quality anti-aliased text rendering
* Real-time CPU and GPU profiling
* User-controlled variables
* Game controller, mouse, and keyboard input
* A friendly DirectXMath wrapper
* Perspective camera supporting traditional and reversed Z matrices
* Asynchronous DDS texture loading and ZLib decompression
* Large library of shaders
* Easy shader embedding via a compile-to-header system
* Easy render target, depth target, and unordered access view creation
* A thread-safe GPU command context system (WIP)
* Easy-to-use dynamic constant buffers and descriptor tables

## Requirements
* Windows 10
* [Visual Studio 2017](https://www.visualstudio.com/) with the [Windows 10 Fall Creators Update SDK](https://developer.microsoft.com/en-US/windows/downloads/windows-10-sdk)

## Contributing
We're always looking for your help to fix bugs and improve the samples.  File those pull requests and we'll be happy to take a look.

Find more information on DirectX 12 on our blog: http://blogs.msdn.com/b/directx/

Troubleshooting information for this repository can be found in the site [Wiki](https://github.com/Microsoft/DirectX-Graphics-Samples/wiki).

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
