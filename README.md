# MiniCoreMC


##Iniciar proyecto en React
https://legacy.reactjs.org/docs/create-a-new-react-app.html



##Montar base de datos Supabase
https://supabase.com/docs/guides/getting-started/tutorials/with-react


npm install @supabase/supabase-js



import { createClient } from '@supabase/supabase-js';

const supabaseUrl = 'URL';
const supabaseKey = 'yourkey';
const supabase = createClient(supabaseUrl, supabaseKey);

export default supabase;




##Deploy
https://www.netlify.com/
