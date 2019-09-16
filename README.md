# Cuda

NVIDIA GPU CUDA library bindings for Erlang and Elixir.

## Installation

```elixir
def deps do
  [{:cuda, "~> 0.1.0"}]
end
```

## Prerequisite

At least one of video cards should be not in exclusive or prohibited compute
mode. To check your video card mode run:

```sh
nvidia-smi --format=csv --query-gpu="compute_mode"
```

To change comute mode to default run:

```sh
sudo nvidia-smi -c 0
```

## Debugging

To have some debug messages from C++ cuda binding, compile library with
`GPU_DEBUG=1` environment variable like this:

```sh
mix clean
GPU_DEBUG=1 mix compile
```  

Kafka with Elixir  
https://www.youtube.com/playlist?list=PLrTrFnOkIFb1ADZUiyEZdItAjDYnoy6WX  

# Нейронная сеть на Elixir  
https://www.youtube.com/watch?v=cV1QmNF-UTQ&list=PLrTrFnOkIFb1ADZUiyEZdItAjDYnoy6WX&index=3&t=0s  

# Orchestrating Kafka with Elixir   
https://www.youtube.com/watch?v=ArYP2bUwNAc&list=PLrTrFnOkIFb1ADZUiyEZdItAjDYnoy6WX&index=2&t=0s   

# Нейронная сеть на Elixir  
https://github.com/gridgentoo/NeuronNetworksElixir  
 

