# @codewell/render-gate

## Installation

**Alpha version**

```
npm install @codewell/render-gate
```

## Basic Usage

```JSX
import RenderGate from '@codewell/render-gate';

const SomeComponent = (props) => (
  <>
    <RenderGate condition={true}>
      This renders
    </RenderGate>

    <RenderGate condition={false}>
      This does not render
    </RenderGate>
  </>
);

```

## Contribution

Please help by submitting issues and pull requests here on github
Read more on [codewell's webpage](https://codewell.github.io/contribution)
