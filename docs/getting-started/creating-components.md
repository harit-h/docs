---
id: creating-components
title: Creating Components
---

import ExampleButton from '@site/docs/components/examples/react/button.md'
import ShowButton from '@site/docs/components/examples/react/show-button.md'
import BitCreateComponent from '@site/docs/components/components/react/bit-create-component-card.md'
import BitCreateMultipleComponent from '@site/docs/components/components/react/bit-create-multiple-components.md'
import BitCreateButton from '@site/docs/components/components/react/bit-create-button.md'
import Styles from '@site/docs/components/components/styles.md'
import BitTemplates from '@site/docs/components/commands/bit-templates.md'
import NameSpaces from '@site/docs/components/components/namespaces.md'
import BitShow from '@site/docs/components/components/bit-show.md'
import BitmapExample from '@site/docs/components/components/bitmap-example.md'
import BitCreateWarning from '@site/docs/components/components/bit-create-warning.md'
import StartDevServer from '@site/docs/components/workspace/starting-dev-server.md'
import Path from '@site/docs/components/components/path.md'

import TestDependencies from '@site/docs/components/components/react/test-dependencies.md'

Once you have [initialized a Bit workspace](/getting-started/initializing-workspace) you can:

1. Use `bit create` to create an example component and add it to the workspace
2. Use `bit install` to install dependencies for test files

Alternatively you can add [pre-existing components](/building-with-bit/pre-existing-components) using the `bit add` command.

## Use Bit Create

<BitCreateButton />

### Namespaces

<NameSpaces />

### Component Location

<Path />

<!-- ### Created Files

The following files will have been created for you:

<ExampleButton />

<Styles /> -->

## Bitmap File

<BitmapExample />

## Install Dependencies

<TestDependencies />

## Show Component

<BitShow />

<ShowButton />

## Starting the Dev Server

<StartDevServer />

## Creating more Components

<BitCreateComponent />

<BitCreateMultipleComponent />

<BitCreateWarning />

## Bit Templates

<BitTemplates />

## What's Next?

Once you have created and added your component to the workspace the next step is to [render the Workspace UI](workspace-ui) so you can see the component locally.

Learn more about [tracking components](/building-with-bit/tracking-components) and [removing components](/building-with-bit/removing-components)
