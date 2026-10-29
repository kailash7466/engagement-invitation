# मंगल निमंत्रण

मराठी विवाह / साखरपुडा निमंत्रण. ही रेपॉझिटरी GitHub Pages वर चालते.

## फाइल्स
- `index.html` – संपूर्ण निमंत्रण आणि एडिटर (एकाच फाइलमध्ये)
- `.nojekyll` – GitHub ला फाइल जशी आहे तशी वापरायला सांगते
- `music.mp3` – एडिटरमधून मोठे गाणे जोडल्यास ही फाइल आपोआप तयार होते

## सुरू करण्याचे टप्पे
1. GitHub वर नवीन **public** रेपॉझिटरी बनवा (उदा. `invite`).
2. **Add file → Upload files** मधून `index.html` आणि `.nojekyll` टाका, मग **Commit changes**.
3. **Settings → Pages**: Source = *Deploy from a branch*, Branch = `main`, Folder = `/ (root)` → **Save**.
4. १–२ मिनिटांनी लिंक तयार: `https://युजरनेम.github.io/रेपॉझिटरी/`

## एडिटर वापरणे
- लिंकच्या शेवटी `#edit` लावा: `https://युजरनेम.github.io/invite/#edit`
- माहिती, फोटो, गाणे, रंग बदला. **पूर्वावलोकन** दाबून पाहुण्यांना कसे दिसेल ते पाहा.
- **पाठवा** विभागात युजरनेम, रेपॉझिटरीचे नाव आणि Access token भरा, मग **GitHub वर प्रकाशित करा** दाबा.
- बदल दिसायला १–२ मिनिटे लागतात.

## Access token कसा बनवायचा
GitHub → Settings → Developer settings → Personal access tokens → **Fine-grained tokens** → Generate new token
- Repository access: फक्त ही रेपॉझिटरी
- Permissions → **Contents: Read and write**

Token फक्त तुमच्या ब्राउझरमध्ये राहतो. तो कोणालाही देऊ नका.

## पाहुण्यांसाठी वेगळी लिंक
एडिटरच्या **पाठवा** विभागात पाहुण्यांची नावे आणि मोबाईल नंबर टाका. प्रत्येकासाठी `…/invite/#नाव` अशी लिंक आणि WhatsApp बटण मिळते. मोबाईल नंबर तुमच्या ब्राउझरमध्येच राहतात.
