## API Report File for "@fluentui/react-tag-picker-preview"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts

/// <reference types="react" />

import type { ActiveDescendantContextValue } from '@fluentui/react-aria';
import { ComboboxProps } from '@fluentui/react-combobox';
import { ComboboxSlots } from '@fluentui/react-combobox';
import type { ComboboxState } from '@fluentui/react-combobox';
import { ComponentProps } from '@fluentui/react-utilities';
import { ComponentState } from '@fluentui/react-utilities';
import { DropdownProps } from '@fluentui/react-combobox';
import { DropdownSlots } from '@fluentui/react-combobox';
import type { ForwardRefComponent } from '@fluentui/react-utilities';
import type { Listbox } from '@fluentui/react-combobox';
import type { ListboxContextValue } from '@fluentui/react-combobox';
import { OptionProps } from '@fluentui/react-combobox';
import { OptionSlots } from '@fluentui/react-combobox';
import { OptionState } from '@fluentui/react-combobox';
import { PortalProps } from '@fluentui/react-portal';
import type { PositioningShorthand } from '@fluentui/react-positioning';
import * as React_2 from 'react';
import { Slot } from '@fluentui/react-utilities';
import type { SlotClassNames } from '@fluentui/react-utilities';
import { TagGroupContextValues } from '@fluentui/react-tags';
import type { TagGroupProps } from '@fluentui/react-tags';
import type { TagGroupSlots } from '@fluentui/react-tags';
import type { TagGroupState } from '@fluentui/react-tags';

// @public (undocumented)
export const iconSizes: {
    small: string;
    medium: string;
    large: string;
};

// @public (undocumented)
export type PickerContextValues = {
    picker: TagPickerContextValue;
    activeDescendant: ActiveDescendantContextValue;
    listbox: ListboxContextValue;
};

// @public
export const renderTagPicker_unstable: (state: TagPickerState, contexts: PickerContextValues) => JSX.Element;

// @public
export const renderTagPickerButton_unstable: (state: TagPickerButtonState) => JSX.Element;

// @public
export const renderTagPickerControl_unstable: (state: TagPickerControlState, contexts: TagPickerControlContextValues) => JSX.Element;

// @public (undocumented)
export function renderTagPickerGroup_unstable(state: TagPickerGroupState, contexts: TagGroupContextValues): JSX.Element | null;

// @public
export const renderTagPickerInput_unstable: (state: TagPickerInputState) => JSX.Element;

// @public
export const renderTagPickerList_unstable: (state: TagPickerListState) => JSX.Element | null;

// @public
export const renderTagPickerOption_unstable: (state: TagPickerOptionState) => JSX.Element;

// @public
export const TagPicker: React_2.FC<TagPickerProps>;

// @public
export const TagPickerButton: ForwardRefComponent<TagPickerButtonProps>;

// @public (undocumented)
export const tagPickerButtonClassNames: SlotClassNames<TagPickerButtonSlots>;

// @public
export type TagPickerButtonProps = ComponentProps<TagPickerButtonSlots> & Pick<DropdownProps, 'clearable' | 'size' | 'appearance'> & {
    disabled?: boolean;
};

// @public (undocumented)
export type TagPickerButtonSlots = {
    root: Slot<'button'>;
} & Pick<DropdownSlots, 'expandIcon' | 'clearButton'>;

// @public
export type TagPickerButtonState = ComponentState<TagPickerButtonSlots> & Pick<TagPickerControlContextValue, 'size' | 'clearable' | 'disabled'> & {
    showClearIcon: boolean;
    hasSelectedOption: boolean;
};

// @public
export const TagPickerControl: ForwardRefComponent<TagPickerControlProps>;

// @public (undocumented)
export const tagPickerControlClassNames: SlotClassNames<TagPickerControlSlots>;

// @public (undocumented)
export type TagPickerControlContextValues = {
    pickerControl: TagPickerControlContextValue;
};

// @public
export type TagPickerControlProps = ComponentProps<TagPickerControlSlots> & Pick<ComboboxProps, 'appearance' | 'size' | 'disabled' | 'clearable'> & {};

// @public (undocumented)
export type TagPickerControlSlots = {
    root: Slot<'div'>;
};

// @public
export type TagPickerControlState = ComponentState<TagPickerControlSlots> & Required<Pick<TagPickerControlProps, 'appearance' | 'size' | 'disabled' | 'clearable'>>;

// @public
export const TagPickerGroup: ForwardRefComponent<TagPickerGroupProps>;

// @public (undocumented)
export const tagPickerGroupClassNames: SlotClassNames<TagPickerGroupSlots>;

// @public
export type TagPickerGroupProps = Omit<TagGroupProps, 'onDismiss' | 'size'>;

// @public (undocumented)
export type TagPickerGroupSlots = TagGroupSlots;

// @public
export type TagPickerGroupState = TagGroupState & {
    hasSelectedOptions: boolean;
};

// @public
export const TagPickerInput: ForwardRefComponent<TagPickerInputProps>;

// @public (undocumented)
export const tagPickerInputClassNames: SlotClassNames<TagPickerInputSlots>;

// @public
export type TagPickerInputProps = Omit<ComponentProps<Partial<TagPickerInputSlots>>, 'children' | 'size' | 'defaultValue'> & Pick<ComboboxProps, 'clearable' | 'size' | 'appearance'> & {
    freeform?: boolean;
    disabled?: boolean;
    value?: string;
};

// @public (undocumented)
export type TagPickerInputSlots = {
    root: Slot<'input'>;
} & Pick<ComboboxSlots, 'clearIcon' | 'expandIcon'>;

// @public
export type TagPickerInputState = ComponentState<TagPickerInputSlots> & Pick<TagPickerControlContextValue, 'size' | 'clearable' | 'disabled'> & {
    showClearIcon: boolean;
};

// @public
export const TagPickerList: ForwardRefComponent<TagPickerListProps>;

// @public (undocumented)
export const tagPickerListClassNames: SlotClassNames<TagPickerListSlots>;

// @public
export type TagPickerListProps = ComponentProps<TagPickerListSlots> & {};

// @public (undocumented)
export type TagPickerListSlots = {
    root: Slot<typeof Listbox>;
};

// @public
export type TagPickerListState = ComponentState<TagPickerListSlots> & Pick<TagPickerContextValue, 'open'>;

// @public
export const TagPickerOption: ForwardRefComponent<TagPickerOptionProps>;

// @public (undocumented)
export const tagPickerOptionClassNames: SlotClassNames<TagPickerOptionSlots>;

// @public
export type TagPickerOptionProps = ComponentProps<TagPickerOptionSlots> & Omit<OptionProps, 'checkIcon'> & {
    children: React_2.ReactNode;
    text?: string;
    value: string;
};

// @public (undocumented)
export type TagPickerOptionSlots = Omit<OptionSlots, 'checkIcon'> & {
    media?: Slot<'div'>;
    secondaryContent?: Slot<'span'>;
};

// @public
export type TagPickerOptionState = ComponentState<TagPickerOptionSlots> & Omit<OptionState, 'checkIcon'>;

// @public
export type TagPickerProps = ComponentProps<TagPickerSlots> & Omit<ComboboxProps, 'size' | 'value'> & Pick<Partial<TagPickerContextValue>, 'size'> & {
    children: [JSX.Element, JSX.Element] | JSX.Element;
};

// @public (undocumented)
export type TagPickerSlots = {};

// @public
export type TagPickerState = ComponentState<TagPickerSlots> & Omit<ComboboxState, 'listbox' | 'root' | 'input' | 'expandIcon' | 'clearIcon' | 'components' | 'size'> & Pick<TagPickerContextValue, 'triggerRef' | 'popoverId' | 'popoverRef' | 'targetRef' | 'size'> & {
    positioning?: PositioningShorthand;
    trigger: React_2.ReactNode;
    popover: React_2.ReactNode;
};

// @public
export const useTagPicker_unstable: (props: TagPickerProps) => TagPickerState;

// @public
export const useTagPickerButton_unstable: (props: TagPickerButtonProps, ref: React_2.Ref<HTMLButtonElement>) => TagPickerButtonState;

// @public
export const useTagPickerButtonStyles_unstable: (state: TagPickerButtonState) => TagPickerButtonState;

// @public
export const useTagPickerControl_unstable: (props: TagPickerControlProps, ref: React_2.Ref<HTMLDivElement>) => TagPickerControlState;

// @public
export const useTagPickerControlStyles_unstable: (state: TagPickerControlState) => TagPickerControlState;

// @public
export const useTagPickerGroup_unstable: (props: TagPickerGroupProps, ref: React_2.Ref<HTMLDivElement>) => TagPickerGroupState;

// @public
export const useTagPickerGroupStyles_unstable: (state: TagPickerGroupState) => TagPickerGroupState;

// @public
export const useTagPickerInput_unstable: (props: TagPickerInputProps, ref: React_2.Ref<HTMLDivElement>) => TagPickerInputState;

// @public
export const useTagPickerInputStyles_unstable: (state: TagPickerInputState) => TagPickerInputState;

// @public
export const useTagPickerList_unstable: (props: TagPickerListProps, ref: React_2.Ref<HTMLDivElement>) => TagPickerListState;

// @public
export const useTagPickerListStyles_unstable: (state: TagPickerListState) => TagPickerListState;

// @public
export const useTagPickerOption_unstable: (props: TagPickerOptionProps, ref: React_2.Ref<HTMLDivElement>) => TagPickerOptionState;

// @public
export const useTagPickerOptionStyles_unstable: (state: TagPickerOptionState) => TagPickerOptionState;

// (No @packageDocumentation comment for this package)

```