# C++ Monolith App Template

## Getting Started

1. Open the project in the VSCode.

2. Click "Reopen in Container" in a VSCode notification.

3. Do `bash ci/prepare.sh`.

4. Do `bash ci/precommit.sh`.

5. Replace `monolith` and `MONOLITH` with your project name.

6. Repeat steps 1-4.

## Notes

- Application executable is available at `{build_dir}/source/{project_name}`.

- To enable `benchmark` module configure the project with `{project_name}_BENCHMARK=ON`.

- Benchmark executables are available at `{build_dir}/benchmark/{project_name}-bench-{bench_name}`.

- Do not forget to use `Asan` build mode.
