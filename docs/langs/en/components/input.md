---
title: Link
lang: zh
---

<script setup lang="ts">
  import props from "../../../example/input/description/en-props.ts";
  import events from "../../../example/input/description/en-events.ts";
</script>


# Input

Enter characters through the keyboard

# Basic Usage

<demo src="../../../example/input/base.vue"></demo>


# Disabled state

Disable the input box through the ```disabled``` property
<demo src="../../../example/input/disabled.vue"></demo>

# Empty the content

Empty the input box with one click through the ```clearable``` attribute
<demo src="../../../example/input/clear.vue"></demo>

# Icon input box

Add custom icons on both sides of the input box via the ```prefixIcon``` and  ```suffixIcon``` attributes
<demo src="../../../example/input/icon.vue"></demo>

# Password

Get an input box that can switch the hidden password through the ```type``` attribute.

<demo src="../../../example/input/password.vue"></demo>

## Attributes
<table-block type="propsEn" :data="props"></table-block>

## Events
<table-block type="eventsEn" :data="events"></table-block>


