# Drizzle ORM Snippets

[![Visual Studio Marketplace Version](https://img.shields.io/visual-studio-marketplace/v/imgildev.vscode-drizzle-snippets?style=for-the-badge&label=VS%20Marketplace&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-drizzle-snippets)
[![Visual Studio Marketplace Installs](https://img.shields.io/visual-studio-marketplace/i/imgildev.vscode-drizzle-snippets?style=for-the-badge&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-drizzle-snippets)
[![Visual Studio Marketplace Downloads](https://img.shields.io/visual-studio-marketplace/d/imgildev.vscode-drizzle-snippets?style=for-the-badge&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-drizzle-snippets)
[![Visual Studio Marketplace Rating](https://img.shields.io/visual-studio-marketplace/r/imgildev.vscode-drizzle-snippets?style=for-the-badge&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-drizzle-snippets&ssr=false#review-details)
[![GitHub Repo stars](https://img.shields.io/github/stars/ManuelGil/vscode-drizzle-snippets?style=for-the-badge&logo=github)](https://github.com/ManuelGil/vscode-drizzle-snippets)
[![GitHub license](https://img.shields.io/github/license/ManuelGil/vscode-drizzle-snippets?style=for-the-badge&logo=github)](https://github.com/ManuelGil/vscode-drizzle-snippets/blob/main/LICENSE)

> A Visual Studio Code extension that provides a comprehensive set of snippets for Drizzle ORM, streamlining the creation of database schema and query builder code.

## Overview

Drizzle ORM Snippets accelerates development by offering:

- **Schema Definitions**: Snippets for column types (e.g., `dz_varchar`, `dz_timestamp`, `dz_boolean`).
- **Relations & Constraints**: Shortcuts for foreign keys, defaults, and enums (`dz_references`, `dz_pgEnum`).
- **Query Builder Methods**: Common operations such as `select`, `join`, `where`, `limit`, and conflict handling.
- **Fluent API Calls**: Conditionals and logical operators (`dz_eq`, `dz_and`, `dz_array_overlaps`, etc.).

Rather than memorizing lengthy method names, type a prefix (such as `dz_varchar`) and press **Tab** or **Enter** to expand.

## Requirements

- Visual Studio Code 1.46.0 or later (compatible with VSCodium, WindSurf, Cursor, etc.)

## Installation

1. Open **Visual Studio Code**.
2. Navigate to the **Extensions** view (`Ctrl+Shift+X` on Windows/Linux or `⌘+Shift+X` on macOS).
3. Search for **Drizzle ORM Snippets** or install directly from the [Marketplace](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-drizzle-snippets).
4. Click **Install** and reload the editor if prompted.

## Usage

1. Open or create a TypeScript or JavaScript file in your Drizzle ORM project.
2. Type a snippet prefix and press **Tab** or **Enter** to insert the corresponding code.

### Example Snippet Prefixes


| Snippet                    | Purpose              |
| -------------------------- | -------------------- |
| dz_id_serial               | id serial            |
| dz_id_bigint               | id bigint            |
| dz_binary                  | binary               |
| dz_bigserial               | bigserial            |
| dz_boolean                 | boolean              |
| dz_blob                    | blob                 |
| dz_char                    | char                 |
| dz_cidr                    | cidr                 |
| dz_date                    | date                 |
| dz_datetime                | datetime             |
| dz_decimal                 | decimal              |
| dz_double                  | double               |
| dz_doublePrecision         | doublePrecision      |
| dz_pgEnum                  | pgEnum               |
| dz_float                   | float                |
| dz_inet                    | inet                 |
| dz_int                     | int                  |
| dz_integer                 | integer              |
| dz_interval                | interval             |
| dz_json                    | json                 |
| dz_jsonb                   | jsonb                |
| dz_macaddr                 | macaddr              |
| dz_macaddr8                | macaddr8             |
| dz_mediumint               | mediumint            |
| dz_numeric                 | numeric              |
| dz_real                    | real                 |
| dz_serial                  | serial               |
| dz_smallint                | smallint             |
| dz_smallserial             | smallserial          |
| dz_text                    | text                 |
| dz_tinytext                | tinytext             |
| dz_mediumtext              | mediumtext           |
| dz_longtext                | longtext             |
| dz_time                    | time                 |
| dz_timestamp               | timestamp            |
| dz_tinyint                 | tinyint              |
| dz_uuid                    | uuid                 |
| dz_varbinary               | varbinary            |
| dz_varchar                 | varchar              |
| dz_year                    | year                 |
| dz_references              | int references       |
| dz_select                  | select               |
| dz_select_distinct         | selectDistinct       |
| dz_select_distinct_on      | selectDistinctOn     |
| dz_limit                   | limit                |
| dz_order_by                | orderBy              |
| dz_group_by                | groupBy              |
| dz__with                   | $with                |
| dz_with                    | with                 |
| dz_update                  | update               |
| dz_insert                  | insert               |
| dz_on_conflict_do_nothing  | onConflictDoNothing  |
| dz_on_conflict_do_update   | onConflictDoUpdate   |
| dz_on_duplicate_key_update | onDuplicateKeyUpdate |
| dz_delete                  | delete               |
| dz_left_join               | leftJoin             |
| dz_right_join              | rightJoin            |
| dz_inner_join              | innerJoin            |
| dz_full_join               | fullJoin             |
| dz_eq                      | eq                   |
| dz_ne                      | ne                   |
| dz_gt                      | gt                   |
| dz_gte                     | gte                  |
| dz_lt                      | lt                   |
| dz_lte                     | lte                  |
| dz_is_null                 | isNull               |
| dz_is_not_null             | isNotNull            |
| dz_in_array                | inArray              |
| dz_not_in_array            | notInArray           |
| dz_exists                  | exists               |
| dz_not_exists              | notExists            |
| dz_between                 | between              |
| dz_not_between             | notBetween           |
| dz_like                    | like                 |
| dz_ilike                   | ilike                |
| dz_not_ilike               | notIlike             |
| dz_not                     | not                  |
| dz_and                     | and                  |
| dz_or                      | or                   |
| dz_array_contains          | arrayContains        |
| dz_array_contained         | arrayContained       |
| dz_array_overlaps          | arrayOverlaps        |

## Contributing

Contributions to the Drizzle ORM Snippets are welcome and appreciated. To contribute:

1. Fork the [GitHub repository](https://github.com/ManuelGil/vscode-drizzle-snippets).
2. Create a new branch for your feature or fix:

   ```bash
   git checkout -b feature/your-feature
   ```

3. Make your changes, commit them, and push to your fork.
4. Submit a Pull Request targeting the `main` branch.

Before contributing, please review the [Contribution Guidelines](https://github.com/ManuelGil/vscode-drizzle-snippets/blob/main/CONTRIBUTING.md) for coding standards, testing, and commit message conventions. If you encounter a bug or wish to request a new feature, please open an Issue.

## Changelog

For a complete list of changes, see the [CHANGELOG.md](https://github.com/ManuelGil/vscode-drizzle-snippets/blob/main/CHANGELOG.md).

## Authors

- **Manuel Gil** - _Owner_ - [@ManuelGil](https://github.com/ManuelGil)

For a complete list of contributors, please refer to the [contributors](https://github.com/ManuelGil/vscode-drizzle-snippets/contributors) page.

## Follow Me

- **GitHub**: [![GitHub followers](https://img.shields.io/github/followers/ManuelGil?style=for-the-badge\&logo=github)](https://github.com/ManuelGil)
- **X (formerly Twitter)**: [![X Follow](https://img.shields.io/twitter/follow/imgildev?style=for-the-badge\&logo=x)](https://twitter.com/imgildev)

## Other Extensions

- **[Auto Barrel](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-auto-barrel)**
  Automatically generates and maintains barrel (`index.ts`) files for your TypeScript projects.

- **[Angular File Generator](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-angular-generator)**
  Generates boilerplate and navigates your Angular (9→20+) project from within the editor, with commands for components, services, directives, modules, pipes, guards, reactive snippets, and JSON2TS transformations.

- **[NestJS File Generator](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-nestjs-generator)**
  Simplifies creation of controllers, services, modules, and more for NestJS projects, with custom commands and Swagger snippets.

- **[NestJS Snippets](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-nestjs-snippets-extension)**
  Ready-to-use code patterns for creating controllers, services, modules, DTOs, filters, interceptors, and more in NestJS.

- **[T3 Stack / NextJS / ReactJS File Generator](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-nextjs-generator)**
  Automates file creation (components, pages, hooks, API routes, etc.) in T3 Stack (Next.js, React) projects and can start your dev server from VSCode.

- **[Drizzle ORM Snippets](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-drizzle-snippets)**
  Collection of code snippets to speed up Drizzle ORM usage, defines schemas, migrations, and common database operations in TypeScript/JavaScript.

- **[CodeIgniter 4 Spark](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-codeigniter4-spark)**
  Scaffolds controllers, models, migrations, libraries, and CLI commands in CodeIgniter 4 projects using Spark, directly from the editor.

- **[CodeIgniter 4 Snippets](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-codeigniter4-snippets)**
  Snippets for accelerating development with CodeIgniter 4, including controllers, models, validations, and more.

- **[CodeIgniter 4 Shield Snippets](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-codeigniter4-shield-snippets)**
  Snippets tailored to CodeIgniter 4 Shield for faster authentication and security-related code.

- **[Mustache Template Engine - Snippets & Autocomplete](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-mustache-snippets)**
  Snippets and autocomplete support for Mustache templates, making HTML templating faster and more reliable.

## Recommended Browser Extension

For developers who work with `.vsix` files for offline installations or distribution, the complementary [**One-Click VSIX**](https://chromewebstore.google.com/detail/imojppdbcecfpeafjagncfplelddhigc?utm_source=item-share-cb) extension is recommended, available for both Chrome and Firefox.

> **One-Click VSIX** integrates a direct "Download Extension" button into each VSCode Marketplace page, ensuring the file is saved with the `.vsix` extension, even if the server provides a `.zip` archive. This simplifies the process of installing or sharing extensions offline by eliminating the need for manual file renaming.

- [Get One-Click VSIX for Chrome &rarr;](https://chromewebstore.google.com/detail/imojppdbcecfpeafjagncfplelddhigc?utm_source=item-share-cb)
- [Get One-Click VSIX for Firefox &rarr;](https://addons.mozilla.org/es-ES/firefox/addon/one-click-vsix/)

## License

This project is licensed under the **MIT License**. See the [LICENSE](https://github.com/ManuelGil/vscode-drizzle-snippets/blob/main/LICENSE) file for full details.
