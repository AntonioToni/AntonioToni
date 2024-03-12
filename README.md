```ts
/**
 * Hi there! 👋
 * 
 * My name is Antonio, a passionate Computer Science student from Croatia.
 * Here's a glimpse of what I bring to the table:
 */

import { Skills, Frameworks, Tools } from './types';

const aboutMe: string = `
I'm currently diving deep into the world of software development, exploring various technologies
and honing my skills to become a proficient developer.
`;

const mySkills: Skills[] = [
  'TypeScript',
  'JavaScript',
  'HTML',
  'CSS',
  'Markdown'
];

const frameworks: Frameworks[] = [
  'ReactJS',
  'Express'
];

const stylingLibraries: Frameworks[] = [
  'MaterialUI'
];

const tools: Tools[] = [
  'Visual Studio Code'
];

console.log('Thanks for stopping by! Feel free to reach out for collaboration or just to say hello.');

export {
  aboutMe,
  mySkills,
  frameworks,
  stylingLibraries,
  tools
};

```
