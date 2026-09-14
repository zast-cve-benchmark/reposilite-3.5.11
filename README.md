# reposilite-3.5.11 - 漏洞总览

| # | CVE | 端点 | 漏洞类型 | 状态 |
|---|---|---|---|---|
| 1 | CVE-2024-36115 | `GET /{repository}/<gav>`（同 `PUT/POST /{repository}/<gav>` 注入） | 存储型跨站脚本 (CWE-79) | CODE_AUDIT |
| 2 | CVE-2024-36116 | `GET /javadoc/{repository}/<gav>` | 路径遍历/任意文件上传 (CWE-22) | CODE_AUDIT |
| 3 | CVE-2024-36117 | `GET /javadoc/{repository}/<gav>/raw/<resource>` | 路径遍历/任意文件读取 (CWE-22) | CODE_AUDIT |
| 4 | GHSA-W7C4-5W4F-JM3G | `GET /javadoc/{repository}/<gav>/raw/<resource>` | 路径遍历/任意文件读取 (CWE-22, 撤回重复公告=CVE-2024-36117) | CODE_AUDIT |
