# On: Garrison Hill
<details> 
<summary>More</summary>
<br>Main
<br>Why?
<br>How?
<br>Latest?
<br>Archives? 
import grapejs, {editor} from 'grapejs';
import GjsEditor from '@grapejs/react';

export default function DefaultEditor () {
  const onEditor = (editor: Editor) => {
    console.log('Editor loaded', {editor});
  };

  return (
    <GjsEditor
     grapejs={grapejs}
     grapejsCss= "https://unpkg.com/grapejs/dist/css/grapes.min.css"
     onEditor-{onEditor}
     options={{
       height: '100vh',
       storageManage: false,
      }}
    >
        <div>
            <Canvas>
        <div>
      </GjsEditor>
    );
  }
