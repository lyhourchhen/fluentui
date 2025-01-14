## API Report File for "@fluentui/react-avatar"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts

import { ComponentPropsCompat } from '@fluentui/react-utilities';
import { ComponentStateCompat } from '@fluentui/react-utilities';
import { PresenceBadgeProps } from '@fluentui/react-badge';
import { PresenceBadgeStatus } from '@fluentui/react-badge';
import * as React_2 from 'react';
import { ShorthandPropsCompat } from '@fluentui/react-utilities';

// @public (undocumented)
export const Avatar: React_2.ForwardRefExoticComponent<AvatarProps & React_2.RefAttributes<HTMLElement>>;

// @public
export type AvatarDefaultedProps = 'size' | 'color' | 'activeDisplay' | 'getInitials' | 'label' | 'icon';

// @public
export type AvatarNamedColor = 'darkRed' | 'cranberry' | 'red' | 'pumpkin' | 'peach' | 'marigold' | 'gold' | 'brass' | 'brown' | 'forest' | 'seafoam' | 'darkGreen' | 'lightTeal' | 'teal' | 'steel' | 'blue' | 'royalBlue' | 'cornflower' | 'navy' | 'lavender' | 'purple' | 'grape' | 'lilac' | 'pink' | 'magenta' | 'plum' | 'beige' | 'mink' | 'platinum' | 'anchor';

// @public (undocumented)
export interface AvatarProps extends ComponentPropsCompat, React_2.HTMLAttributes<HTMLElement> {
    active?: 'active' | 'inactive' | 'unset';
    activeDisplay?: 'ring' | 'shadow' | 'glow' | 'ring-shadow' | 'ring-glow';
    badge?: PresenceBadgeStatus | Exclude<ShorthandPropsCompat<PresenceBadgeProps>, string>;
    color?: 'neutral' | 'brand' | 'colorful' | AvatarNamedColor;
    getInitials?: (name: string, isRtl: boolean) => string;
    icon?: ShorthandPropsCompat<React_2.HTMLAttributes<HTMLElement>>;
    idForColor?: string;
    image?: ShorthandPropsCompat<React_2.ImgHTMLAttributes<HTMLImageElement>>;
    label?: ShorthandPropsCompat<React_2.HTMLAttributes<HTMLElement>>;
    name?: string;
    size?: AvatarSizeValue;
    square?: boolean;
}

// @public
export type AvatarShorthandPropsCompat = 'label' | 'image' | 'badge' | 'icon';

// @public
export const avatarShorthandPropsCompat: AvatarShorthandPropsCompat[];

// @public
export type AvatarSizeValue = 20 | 24 | 28 | 32 | 36 | 40 | 48 | 56 | 64 | 72 | 96 | 120 | 128;

// @public (undocumented)
export interface AvatarState extends ComponentStateCompat<AvatarProps, AvatarShorthandPropsCompat, AvatarDefaultedProps> {
    ref: React_2.Ref<HTMLElement>;
    showIcon?: boolean;
}

// @public (undocumented)
export const renderAvatar: (state: AvatarState) => JSX.Element;

// @public (undocumented)
export const useAvatar: (props: AvatarProps, ref: React_2.Ref<HTMLElement>, defaultProps?: AvatarProps | undefined) => AvatarState;

// @public (undocumented)
export const useAvatarStyles: (state: AvatarState) => AvatarState;

// (No @packageDocumentation comment for this package)

```
