# epitechIntranetApi
Api for Epitech Intranet
    https://www.npmjs.com/package/epitech_intranet_api
# Install
    npm i epitech_intranet_api
# Use it:
        
        const IntraApiEpi = require("epitechIntranetApi");

        const intra = new IntranetApi("Your autologin");

# User:
    getProfile
        intra.user.getProfile() returns important information about the user
    getGpa
        intra.user.getGpa() return the user GPA
    getCredits
        intra.user.getCredits() return the user Crédits
    getPromo
        intra.user.getPromo() return the user Promo
    getScolarYear
        intra.user.getScolarYear() return the user ScolarYear
    getEpitechEmail
        intra.user.getEpitechEmail() return the user Epitech Email
    getBinomes
        intra.user.getBinomes() return the user Binomes
    getFlags
        intra.user.getFlags() return all the user Flags
        intra.user.getFlags("medal") return the user Medail Flags
        intra.user.getFlags("remarkable") return the user Remarkable Flags
        intra.user.getFlags("difficulty") return the user Difficulty Flags
        intra.user.getFlags("ghost") return the user Ghost Flags
    getPicture
        intra.user.getPicture() return the user url Picture
