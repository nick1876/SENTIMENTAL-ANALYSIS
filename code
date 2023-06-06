print("Welcome to our Sentimental Analysis!!!")
for q in range(0,1000,1):
    x = input("Enter any sentence : ") # input a sentence
    l1 = len(x) # length of sentence(characters) entered
    s=''
    for f in range(l1):
        if(x[f]=='.' or x[f]==',' or x[f]=='!' or x[f]=='?' or x[f]=='/'):
            s=s+' '
        else:
            s=s+x[f]
    l = s.split() # sentence convering into list
    len0 = len(l) # length of list
    p = 0 # counter variable for positive words in the list
    n = 0 # counter variable for negative words in the list
    pos = ['Adaptable','Like','Bitch','Applause','Applauding','Adventurous','Better','Amazing','Amiable','Beautiful','Becoming','Beloved','Best','Blessed','Blissful','Brave','Brotherly','Calming','Captivating','Charming','Cherished','Comforting','Compelling','Considerable','Credible','Congrats','Congratulation','Congratulations','Dapper','Darling','Delicious','Delightful','Dependable','Desirable','Dreamy','Durable','Elegant','Empowering','Enchanting','Endearing','Energising','Enjoyable','Enlightening','Exceptional','Exciting','Excited','Fabulous','Fancy','Fantastic','Fashionable','Faultless','Fetching','Flourishing','Formidable','Fulfilling','Funny','Generous','Gifted','Glamorous','Gleaming','Glowing','Good','Godly','Gracious','Gratifying','Happy','Happening','Harmonious','Heavenly','Historic','Honourable','Humble','Ideal','Important','Incredible','Indispensable','Indisputable','Influential','Inspiring','Inspiration','Interesting','Intelligent','Irresistible','Joyful','Jolly','Jovial','Kindly','Kingly','Leading','Legendary','Liberating','Likeable','Lordly','Lovable','Luscious','Luxurious','Magical','Majestic','Memorable','Mesmerizing','Mighty','Miraculous','Motivational','Nifty','Obliging','Optimal','Original','Outgoing','Palatable','Paramount','Peaceful','Peachy','Perfect','Phenomenal','Picturesque','Pleasant','Pleasing','Pleasurable','Positive','Powerful','Praiseworthy','Precious','Prestigious','Prizewinning','Promising','Proud','Quality','Radiant','Reasonable','Refreshing','Reliable','Respectable','Revolutionary','Rewarding','Rousing','Saintly','Salubrious','Satisfying','Save','Scrumptious','Sensational','Sexy','Shiny','Showy','Smashing','Soothing','Sought-after','Spectacular','Spiffy','Stimulating','Striking','Stunning','Stupendous','Superb','Supreme','Swanky','Tasteful','Tasty','Terrific','Thank','Thanks','Thanking','Thrilling','Titillating','Tremendous','Trusty','Ultimate','Unbelievable','Uplifting','Useful','Valuable','Vibrant','Victory','Victorious']
    len1= len(pos)
    str1 = ','
    str4 = ''
    for i in range(0, len1, 1):
        str4 = str4+pos[i]+str1  # list of positive words into string
    po1 = str4.upper()   # for converting all letters in upper case
    posU = po1.split(',')  # for converting upper case string into list again
    po2 = str4.lower()   # for converting all letters in lower case
    posL = po2.split(',')  # for converting lower case string into lhhhist again
    neg = ['Abrasive','Apathetic','Arrest','Controlling','Dishonest','Impatient','Anxious','Betrayed','Disappointed','Embarrassed','Jealous','Abysmal','Bad','Callous','Corrosive','Damage','Despicable','Don’t','Enraged','Fail','Fuck','Gawky','Haggard','Hurt','Icky','Insane','Inflation','Jealous','Lose','Malicious','Naive','Objectionable','Pain','Questionable','Reject','Rude','Sad','Sinister','Stuck','Tense','Ugly','Unsightly','Vice','Wary','Yell','Zero','Adverse','Banal','Can’t','Corrupt','Damaging','Detrimental','Dreadful','Eroding','Faulty','Ghastly','Hard','Hurtful','Ignorant','Insidious','Junky','Lousy','Mean','Nasty','Noxious','Odious','Perturb','Quirky','Renege','Ruthless','Savage','Slimy','Stupid','Terrible','Undermine','Untoward','Vicious','Weary','Yucky','Alarming','Barbed','Clumsy','Dastardly','Dirty','Dreary','Evil','Fear','Grave','Hard-hearted','Ignore','Injure','Insipid','Lumpy','Menacing','Naughty','None','Offensive','Pessimistic','Quit','Repellant','Scare','Smelly','Substandard','Terrifying','Unfair','Unwanted','Vile','Wicked','Angry','Belligerent','Coarse','Crazy','Dead','Disease','Feeble','Greed','Harmful','Ill','Injurious','Messy','Negate','No one','Old','Petty','Reptilian','Scary','Sobbing','Suspect','Sad','Threatening','Unfavorable','Unwelcome','Villainous','Woeful','Annoy','Bemoan','Cold','Creepy','Decaying','Disgusting','Fight','Grim','Hate','Immature','Misshapen','Negative','Nothing','Oppressive','Plain','Repugnant','Scream','Sorry','Suspicious','Smoke','Smoking','Unhappy','Unwholesome','Vindictive','Worthless','Anxious','Beneath','Cold-hearted','Criminal','Deformed','Disheveled','Filthy','Grimace','Hideous','Imperfect','Missing','Never','Neither','Poisonous','Repulsive','Severe','Spiteful','Unhealthy','Unwieldy','Wound','Apathy','Boring','Collapse','Cruel','Deny','Dishonest','Foul','Gross','Homely','Impossible','Misunderstood','No','Nowhere','Poor','Revenge','Shocking','Sticky','Unjust','Unwise','Appalling','Broken','Confused','Cry','Deplorable','Dishonorable','Frighten','Grotesque','Horrendous','Inane','Moan','Nobody','Prejudice','Revolting','Shoddy','Stinky','Unlucky','Upset','Atrocious','Contrary','Cutting','Depressed','Dismal','Frightful','Gruesome','Horrible','Inelegant','Moldy','Nondescript','Rocky','Sick','Stormy','Unpleasant','Awful','Contradictory','Deprived','Distress','Guilty','Hostile','Infernal','Monstrous','Nonsense','Rotten','Sickening','Stressful','Unsatisfactory']
    len2=len(neg)
    str2 = ','
    str3 = ''
    for i in range(0, len2, 1):
        str3 = str3+neg[i]+str2  # list of negative words into string
    ne1 = str3.upper()  # for converting all letters in upper case
    negU = ne1.split(',')  # for converting upper case string into list again
    ne2 = str3.lower()  # for converting all letters in lower case
    negL = ne2.split(',')  # for converting lower case string into list again
    for i in range(0, len0, 1): # checking each word  of the entered sentence with positive and negative words
        for j in range(0, len1, 1): # checking with positive words
            if(l[i] == pos[j] or l[i] == posU[j] or l[i] == posL[j]):
                if i == 0:
                    p += 1
                if i == 1:
                    if(l[i-1] == 'not' or l[i-1] == 'NOT' or l[i-1] == 'Not'):
                        n += 1
                    else:
                        p += 1
                if i > 1:
                    if(l[i-1] == 'not' or l[i-1] == 'NOT' or l[i-1] == 'Not' or l[i-2] == 'not' or l[i-2] == 'NOT' or l[i-2] == 'Not'):
                        n += 1
                    else:
                        p += 1
        for k in range(0, len2, 1): # checking with negative words
            if(l[i] == neg[k] or l[i] == negU[k] or l[i] == negL[k]):
                if i == 0:
                    n += 1
                if i == 1:
                    if(l[i-1] == 'not' or l[i-1] == 'NOT' or l[i-1] == 'Not'):
                        p += 1
                    else:
                        n += 1
                if i > 1:
                    if(l[i-1] == 'not' or l[i-1] == 'NOT' or l[i-1] == 'Not' or l[i-2] == 'not' or l[i-2] == 'NOT' or l[i-2] == 'Not'):
                        p += 1
                    else:
                        n += 1
    if n > p:
        print("This is a negative sentence. ")
    if n < p:
        print("This is a positive sentence. ")
    if n == p:
        print("This is a neutral sentence. ")
    character=input("Do you want to continue...? y for Yes and n for No:  ")
    if(character=='y'):
        print("Welcome to Sentimental Analysis")
    if(character=='n'):
        print("Thank you for using our Sentimental Analysis")
        break
