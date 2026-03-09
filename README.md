# Test Files for Internet Speed Test

Binary files of different sizes for Internet speed testing, aligned with [MCP Internet Speed Test](https://github.com/inventer-dev/mcp-internet-speed-test/).

Files are stored using **Git LFS** (Large File Storage).

## Available files

| File | Size |
|------|------|
| 128KB.bin | 128 KB |
| 256KB.bin | 256 KB |
| 512KB.bin | 512 KB |
| 1MB.bin | 1 MB |
| 2MB.bin | 2 MB |
| 4MB.bin | 4 MB |
| 8MB.bin | 8 MB |
| 16MB.bin | 16 MB |
| 32MB.bin | 32 MB |
| 64MB.bin | 64 MB |
| 128MB.bin | 128 MB |

## How to download files

Since files are stored with Git LFS, the raw GitHub URL returns a **redirect to the actual file content**. Use the `media` endpoint or follow redirects:

### Direct download URL (recommended)

```
https://media.githubusercontent.com/media/inventer-dev/speed-test-files/main/<FILE>
```

Example:

```
https://media.githubusercontent.com/media/inventer-dev/speed-test-files/main/1MB.bin
https://media.githubusercontent.com/media/inventer-dev/speed-test-files/main/8MB.bin
https://media.githubusercontent.com/media/inventer-dev/speed-test-files/main/128MB.bin
```

### Alternative: raw URL with redirect

The standard `raw.githubusercontent.com` URL also works if your HTTP client follows redirects:

```
https://raw.githubusercontent.com/inventer-dev/speed-test-files/main/1MB.bin
```

> **Note:** Some clients (like `fetch` in browsers) follow the redirect automatically. If you get a small text file instead of the binary, you're getting the LFS pointer — use the `media` URL instead.

### Clone with Git LFS

To clone the full repository with all binary files:

```bash
git lfs install
git clone https://github.com/inventer-dev/speed-test-files.git
```
