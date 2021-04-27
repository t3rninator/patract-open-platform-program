# patract-open-platform-program

[中文版本](./README_zh.md)

Welcome to join Patract Open Platform. You can elaborate on the project introduction, Wasm technology roadmap, Wasm technology code display, developer community activities, etc. The updated content will be displayed at http://open.platform.io.

If the description has nothing to do with Wasm contract technology, Patract may modify or delete the content.

## The method for adding your content

1. Fork this repo;

2. Enter the directory `projects`, copy the directory `template` and rename it as your project name. The directory name is only a path name, please fill in lower-case letters;

3. Modify the template content as your project content in the files of `README.md` and `README_zh.md`.The first one is for English content and the last one is for Chinese content. If you do not have Chinese version content, just delete the `README_zh.md` file.

4. The `links_v1.json` file is used for display some website and community links on http://open.platform.io:

   1. The accepted keys is following:

      | website | twitter  | github   | develop_doc | element  | telegram | discord  |
      | ------- | -------- | -------- | ----------- | -------- | -------- | -------- |
      | must    | optional | optional | optional    | optional | optional | optional |

   2. "must" means this link key must be provided, and "optional" means this item could be removed. If you do not provide the optional item, the website would not display this missing link.

5. Create a Pull Request to this repo, we will review your PR and merge it. After a time, it will be updated at http://open.platform.io.

> The example PR could refers to [PR#4](https://github.com/patractlabs/patract-open-platform-program/pull/4), [PR#5](https://github.com/patractlabs/patract-open-platform-program/pull/5)

