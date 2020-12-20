# ts-react-snippets

react typescript snippets


|  Snippet   | Purpose  |
|  ----  | ----  |
| tb-cc  | React Class Component  |
| tb-cpc | React Class PureComponent |
| tb-fc  | React FunctionComponent |

## example

### `tb-cc`
```typescript
import React from 'react'

type Props = {}

type State = {}

export class ComponentName extends React.Component<Props, State> {
  render() {
    
  }
}
```

### `tb-cpc`
```typescript
import React from 'react'

type Props = {}

type State = {}

export class ComponentName extends React.PureComponent<Props, State> {
  render() {
    
  }
}
```

### `tb-fc`
```typescript
import React, { FC } from 'react'

type Props = {}

export const ComponentName: FC<Props> = (props) => {
  return (
    
  )
}
```



