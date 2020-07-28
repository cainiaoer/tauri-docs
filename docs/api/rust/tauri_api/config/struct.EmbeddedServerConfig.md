---
title: "struct.EmbeddedServerConfig"
---

# Struct [tauri_api](/docs/api/rust/tauri_api/../index.html)::​[config](/docs/api/rust/tauri_api/index.html)::​[EmbeddedServerConfig](/docs/api/rust/tauri_api/)

    pub struct EmbeddedServerConfig {
        pub host: String,
        pub port: Port,
    }

The embeddedServer configuration object.

## Fields

`host: String`

The embedded server host.

`port: Port`

The embedded server port. If it's `random`, we'll generate one at runtime.

## Trait Implementations

### `impl Debug for EmbeddedServerConfig`

#### `fn fmt(&self, f: &mut Formatter) -> Result`

Formats the value using the given formatter. [Read more](https://doc.rust-lang.org/nightly/core/fmt/trait.Debug.html#tymethod.fmt)

### `impl<'de> Deserialize<'de> for EmbeddedServerConfig`

#### `fn deserialize<__D>(__deserializer: __D) -> Result<Self, __D::Error> where __D: Deserializer<'de>,`

Deserialize this value from the given Serde deserializer. [Read more](https://docs.rs/serde/1.0.114/serde/de/trait.Deserialize.html#tymethod.deserialize)

### `impl PartialEq<EmbeddedServerConfig> for EmbeddedServerConfig`

#### `fn eq(&self, other: &EmbeddedServerConfig) -> bool`

This method tests for `self` and `other` values to be equal, and is used by `==`. [Read more](https://doc.rust-lang.org/nightly/core/cmp/trait.PartialEq.html#tymethod.eq)

#### `fn ne(&self, other: &EmbeddedServerConfig) -> bool`

This method tests for `!=`.

### `impl StructuralPartialEq for EmbeddedServerConfig`

## Auto Trait Implementations

### `impl RefUnwindSafe for EmbeddedServerConfig`

### `impl Send for EmbeddedServerConfig`

### `impl Sync for EmbeddedServerConfig`

### `impl Unpin for EmbeddedServerConfig`

### `impl UnwindSafe for EmbeddedServerConfig`

## Blanket Implementations

### `impl<T> Any for T where T: 'static + ?Sized,`

#### `fn type_id(&self) -> TypeId`

Gets the `TypeId` of `self`. [Read more](https://doc.rust-lang.org/nightly/core/any/trait.Any.html#tymethod.type_id)

### `impl<T> Borrow<T> for T where T: ?Sized,`

#### `fn borrow(&self) -> &T`

Immutably borrows from an owned value. [Read more](https://doc.rust-lang.org/nightly/core/borrow/trait.Borrow.html#tymethod.borrow)

### `impl<T> BorrowMut<T> for T where T: ?Sized,`

#### `fn borrow_mut(&mut self) -> &mutT`

Mutably borrows from an owned value. [Read more](https://doc.rust-lang.org/nightly/core/borrow/trait.BorrowMut.html#tymethod.borrow_mut)

### `impl<T> DeserializeOwned for T where T: Deserialize<'de>,`

### `impl<T> From<T> for T`

#### `fn from(t: T) -> T`

Performs the conversion.

### `impl<T, U> Into<U> for T where U: From<T>,`

#### `fn into(self) -> U`

Performs the conversion.

### `impl<T, U> TryFrom<U> for T where U: Into<T>,`

#### `type Error = Infallible`

The type returned in the event of a conversion error.

#### `fn try_from(value: U) -> Result<T, <T as TryFrom<U>>::Error>`

Performs the conversion.

### `impl<T, U> TryInto<U> for T where U: TryFrom<T>,`

#### `type Error = <U as TryFrom<T>>::Error`

The type returned in the event of a conversion error.

#### `fn try_into(self) -> Result<U, <U as TryFrom<T>>::Error>`

Performs the conversion.

### `impl<V, T> VZip<V> for T where V: MultiLane<T>,`

#### `fn vzip(self) -> V`
