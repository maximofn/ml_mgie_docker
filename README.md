# ml-mgie docker

Dockerization of the [Hugging Face Cosml-mgiexl Space](https://huggingface.co/spaces/tsujuifu/ml-mgie)

 * Space: [tsujuifu/ml-mgie](https://huggingface.co/spaces/tsujuifu/ml-mgie)

## Requisites

[Docker](https://docs.docker.com/desktop/) and [nvidia container toolkit](https://docs.nvidia.com/datacenter/cloud-native/container-toolkit/latest/install-guide.html) must be installed.

## Usage

You can download the image and run it

```bash
docker pull maximofn/ml_mgie:latest
./run_app.sh
```

### Build the image

Or you can build the image and run it

```bash
./build_docker_image.sh
./run_app.sh
```