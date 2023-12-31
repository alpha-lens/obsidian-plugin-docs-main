# FuzzySuggestModal

Extends `SuggestModal<FuzzyMatch<T>>`

## Constructor

```ts
constructor(app: App);
```

## Methods

### getSuggestions

```ts
getSuggestions(query: string): FuzzyMatch<T>[];
```

### renderSuggestion

```ts
renderSuggestion(item: FuzzyMatch<T>, el: HTMLElement): void;
```

제안 항목을 DOM으로 렌더링합니다.

### onChooseSuggestion

```ts
onChooseSuggestion(item: FuzzyMatch<T>, evt: MouseEvent | KeyboardEvent): void;
```

### getItems

```ts
abstract getItems(): T[];
```

### getItemText

```ts
abstract getItemText(item: T): string;
```

### onChooseItem

```ts
abstract onChooseItem(item: T, evt: MouseEvent | KeyboardEvent): void;
```
